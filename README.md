# Beautycounter Frontend Take Home

What you have before you is a stripped-down product description page (PDP). Except it doesn't work.

The goal of this task is two-fold:
* To make the page work and catch as many of its issues as you can detect (there are **at least** 10 issues, all of different levels of severity).
* To create keyboard accessible tabs for the product's `description` and `ingredients` (adding the `featuredIngredients` is not required).

The kinds of things we look for:
* React/JavaScript Best Practices
* CSS/Sass Best Practices
* Performance
* Accessibility 
* Unit Testing

The requirements for this PDP:
* As a user, I would like to be able to view product details (product details come from `mockData` except for product ratings, which come from an external source)
* As a user, I would like to be able to add items to my bag
* As a user, I would like to add a quantity of items to my bag up to the maximum number allowed for an item
* As a user, I would like to see how many items are in my bag
* As a user, I would like to have separate tabs for `descriptions` and `ingredients` (also from the `mockData`) that are also clickable via the keyboard

Mock-ups can be found below.

NOTE: View Bag functionality has been removed from this PDP in order to decrease the the scope of this project. Adding View Bag functionality is not required.

## Guide for Submission

We're hoping this doesn't take you very long to work on. We'd like for you to work on this for, at most, an hour or two. If you find this taking up a good chunk of your day to make the changes, make a list of the changes you would have made if time hadn't been an issue.

Once you come in for your in-person interview (or "in-person" as this timeline demands), we will discuss your submission and the what you did to fix this PDP.

You have a couple options for submission:

1. Create a `git-bundle` that you can send back to the recruiter via email or cloud storage link.
2. Create a Github repo that includes your changes (if you want to keep your repo private, you can invite `racheltusick`).

## Additional Notes

To make things easier, this PDP was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) so all the things you get for free with that are in this project. Those are listed at the end of this README.

This project also uses [Material-UI React Framework](https://material-ui.com/) and [React Testing Library](https://testing-library.com/docs/react-testing-library/intro). We tend to follow the [AirBnB JavaScript Style Guide](https://github.com/airbnb/javascript).

## Mock-ups

### Mobile
<img src="https://user-images.githubusercontent.com/32176293/134558915-29cedf5b-7511-4d93-8d96-49eccbb04a28.png" width="411" />

### Desktop
<img src="https://user-images.githubusercontent.com/32176293/134559080-8871160f-ac34-4d20-919c-76ac9716faa3.png" width="100%" />

---------

## `create-react-app` Details

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
