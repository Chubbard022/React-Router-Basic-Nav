# React Router Basic Nav

Topics:

* Single Page Applications
* React Router V4 (react-router-dom)
* Routing, declarative component based routing
* Path and Component

## Project Description

* A starter pack project for all things React Router. Learn to set up a basic routing system within an application. Use this application to help guide your learning over the next couple of days.
* **Note** that this project has already been boilerplated for you. There is no need to run any installation steps beyond `yarn install`.

### Initialize Project

* cd into the repository and run `yarn install`
DONE
* run `yarn start`
DONE

### Steps for implementing React Router

* You'll notice we've already installed react-router-dom for you.
DONE
* `import` your BrowserRouter as Router inside your `index.js` file.
DONE
* Wrap your `<App />` component that you're passing to `ReactDOM.render()` with your new `Router` component.
DONE
* open up your chrome `REACT DEV TOOLS` and notice your app is now all wrapped in `BrowserRouter`
DONE
* inside the `REACT DEV TOOLS` expand `<BrowserRouter>` and highlight `<Router>` and notice that here is a `"history"` object on props and a `"match"` object on its state. These two objects are how all of our Router is going to work. 
DONE

### Steps for "Declaring" your routes

* Inside of your `App.js` file `import { Route } from 'react-router-dom';`
DONE
* This is where we're going to declare and specify our router.
DONE
* Create 3 `<Route />` setting their `path` prop equal to `/`, `/about`, `/contact` with their respective components.
DONE
* Be sure to incluce the `exact` prop on the root component for `/` to make sure that it's rendering the exact component and not all the other components.
DONE
* You should now be able to type `/`, `/about`, `/contact` after `localhost:PORT/` to see what's inside
DONE

### Steps for setting up your Navigation

* Inside of `Navigation.js` `import { Link } from 'react-router-dom'`.
DONE
* Declare the `to` as the href on `<Link>` and specify the correct routes for your app to navigate towards.
DONE
* Head over to your app and start navigating. You should be able to see your URLS changing their paths as you go. Each path should display the proper component. 
DONE

### Resources

* [Code Sandbox from Lecture](https://codesandbox.io/s/n58oqgwmP)
* [React Router 4 Quick Start Guide](https://reacttraining.com/react-router/web/guides/quick-start)
