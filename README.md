# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


----------------------
My own comments
----------------------

Tutorial link : https://reactjs.org/tutorial/tutorial.html
### Steps followed

1. Create a new project with `npx create-react-app my-app`
2. Delete all files/folders created by default in my-app/src/
3. Add src/index.css with the code `https://codepen.io/gaearon/pen/oWWQNa?editors=0100`
4. Add src/index.js with the code `https://codepen.io/gaearon/pen/oWWQNa?editors=0010`
5. Import 'react', 'react-dom' and './index.css' in the index.js file
6. Do the part Overview `https://reactjs.org/tutorial/tutorial.html#overview`
7. Do the rest of the tutorial



### Notes

1. In the methods render(), putting the jsx (html-like) codes between parentheses helps to avoid some issues with ';' at the end. It may prevent unwanted breaks
2. Changing an object's property/value without mutations helps in detecting changes in states. Avoid issues with pointers too. See `https://reactjs.org/tutorial/tutorial.html#why-immutability-is-important`
3. Lifting State Up: have the logics and data be unified in a common parent component
4. When adding a constructor to a React.Component, this new constructor should always call Super(props) at the very beginning
5. To add elements to an array, use either push() -it mutates the original array-, or concat() -doesn’t mutate the original array-
6. Keys for items of a list : `https://reactjs.org/tutorial/tutorial.html#picking-a-key` : a special and reserved property in React; cannot be referenced using this.props.key; etc..
7. Each time `setState()` is called in a component this latter is rendered again. In short it is updated

Convert from JavaScript to TypeScript
8. Change to TypeScript : https://create-react-app.dev/docs/adding-typescript/
9. Generate tsconfig.json : https://reactjs.org/docs/static-type-checking.html#configuring-the-typescript-compiler
10. Manually change the .js files into either .ts or .tsx (where JSX is used)
11. Afterwards `npm run build`
12. `npm start`