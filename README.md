<h1>Clicky Game</h1>
<br>
<p>This is memory game that is built with React. It breaks up the application's UI into components, manage component state, and respond to user events.</p>
<p>Your memory becomes a factor as you only want to click on the ones that you haven't clicked on yet. Your current score increases each time you click on a new character. The highest score you can get is 12. If you click on something you already clicked on you will loose and that resets the game. Your highest score is kept.</p>
<br>
<h2>Getting Started</h2>
<p>This app is deployed at Heroku <a href="https://peaceful-escarpment-57164.herokuapp.com/"  target = "_blank">here</a>. Or you can get the app set up on your own local computer.</p>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>
<br>
<h4>App Setup</h4>
<br>
<ul>
<li>Fork a copy to your Github repo and clone it to your computer.</li>

<li>Go to your Git Bash and got to into the folder called <strong>ClickyGame.</strong></li>

<li>To get the packages required to run this app type into the command line <strong> yarn install</strong></li>
</ul>
<br>
<h5>The Character Information</h5>
<ul>
<li>You can find the friend or character information in the package.json file. In this file each friend is given an list of attributes and values including id number, name, image link and click value.</li>

<li>The click value is set for false on each friend until the friend image is clicked on by the user. Once that happens the click value is changed to true and if clicked again it will reset the game.</li>

<li>Since this is the file used to contain the friend information there is no use of a database to set up.</li>
</ul>
<h2>Open in Your Code Editor</h2>
<ul>
<li>Open the ClickyGame folder in your text editor of choice (I suggest either Visual Studio Code or Sublime Text).</li>

<li>Then open your terminal (I use GitBash) and go to the main folder of Clicky-Game</li>

<li>Type yarn start end hit enter</li>

<li>When you are ready to stop the app, in the command line hit control C</li>
</ul>
<br>
# <h6>React will automatically start the app in your browser at http://localhost:3000/ unless you already have something else running on that port in which case it will go to 3001.</h6>





This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
