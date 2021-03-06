## How was it Started?

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.  
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/template/README.md).


You may create subdirectories inside `src`. For faster rebuilds, only files inside `src` are processed by Webpack.  
You need to **put any JS and CSS files inside `src`**, or Webpack won’t see them.

You can, however, create more top-level directories.  
They will not be included in the production build so you can use them for things like documentation.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!


### Integrating Auth

Checkout [the auth recipes](/docs/recipes/auth) for some simple examples of how to integrate auth.

**Warning**: You need to handle the loading state of auth! The recipes go over this, [but as mentioned in this issue here](https://github.com/prescottprue/react-redux-firebase/issues/93), it can seem unclear initially.

### Why Is Recompose Used

There are plenty of reasons to use [recompose](https://github.com/acdlite/recompose) (a utility belt for react components) which are not worth getting into here. The main reason it is used in this example it to keep the focus on the Firestore specific logic.

Another main reason Recompose is popular is that is can easily lead to patterns which greatly improve performance
