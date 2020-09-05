This project is about showing the details based on user selection on offer.

In the project directory, you can run:


### `yarn install` or `npm install`

Run the above command to install all the node modules


### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.


### The Directory Structure is as follows

src-|---actions--------DetailActions.js(This contains the actions to fetch details from API)
    |
    |---components--|--Header/Header.js(this contains the first Portion of Webpage where Header data(Tele number exists))
    |               |
    |               |--Banner/Banner.js(This contains the second Portion on Webpage where we will be showing the data)
    |               |
    |               |--MainContent/MainContent.js (Page 1 Body)
    |               |   (Home Page Body where we will be showing all the cards(DealCard, InfoCard, OfferCard))
    |               |   |--DealCard.js(This contains the deal value and deal text)
    |               |   |--OfferCard.js(This contains the buttons(Internet, Phone, TV))
    |               |   |--InfoCard.js(This will contain all the list about the information)
    |               |
    |               |
    |               |--Details/Details.js (Page 2 Body) when user clicks on buttons(Internet, Phone, TV) in Homepage
    |               |   |--DetailCard/DetailCard.js(This will contain each card display where we will be showing the disclosures and amount)
    |
    |---constants------json/MockData.json(Mock Data for APP)
    |
    |---images---------Phone.svg(images folder)
    |
    |---reducers-------detailsReducer.js(This is the Detail Reducer where we will be using while passing the type and payload from detailAction)
    |
    |---store----------(Main store of APP we will have all the configure store here)
    |
    |---App.js------Entry point to APP





This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
