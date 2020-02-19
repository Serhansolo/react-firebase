
This is a playground project for React in combination with the [Firebase suite](https://firebase.google.com/).

## Firebase Products in use
Currently we are only using the [Firebase Hosting](https://firebase.google.com/products/hosting) product. We have created a staging and production environment. This is a very powerfull product since it makes deployment **very** easy.

You can deploy your app to the right environment just by using `firebase deploy --project=[env alias]` as stated in the last sentance of [this](https://firebase.google.com/docs/cli#use_aliases) description. 

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

### `yarn deploy:stage`
##### *This command will deploy all available firebase products.*

Builds the app using `yarn build` and deploys it to the `staging` environment in Firebase Hosting.

### `yarn deploy:prod`
##### *This command will deploy all available firebase products.*

Builds the app using `yarn build` and deploys it to the `production` environment in Firebase Hosting.


___
> This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
