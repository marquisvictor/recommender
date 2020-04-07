This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `install yarn`

If this is your first time with JavaScript and you don't have Yarn installed on your machine, you can easily install Yarn on Ubuntu by firing up your terminal and running the following commands:

- `curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`
- `echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list`

The above curl commands import yarn's repository's GPG key. 


Now the that repository is added to the system, update the package list and install Yarn with:
- `sudo apt update`
- `sudo apt install yarn`

To verify that Yarn installed successfully, run the following command which will print the Yarn version number:
- `yarn --version`

At the time of writing this README, the latest version of Yarn is `version 1.22.4`.

Once that is done and out of the way, move to your project directory and run `yarn`. Watch it install some other dependencies. 

As soon as that's done installing, you can finally run `yarn start` and open [http://localhost:3000](http://localhost:3000) to view it in the browser.


If on the other hand you're on a Windows OS machine, quite easy. Just follow the steps below.

- Download and install the stable version of [Node.js](https://nodejs.org/en/download/)
- Download and install the stable version of [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
- Restart your computer 
- Move to the project directory 
- Right in that directory, open command prompt and run `yarn`.
- Watch it install its dependencies and setup
- Run `yarn start` and open [http://localhost:3000](http://localhost:3000) to view it in the browser.


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

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

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
