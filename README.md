# react-js

JSX Code:

const App = () => {
    return <div>Hello world!</div>
}
Equivalent JS Code:

const App = () => {
  return React.createElement("div", null, "Hello world!");
};

the State of a component is an object that holds some information that may change over the lifetime of the componen
Props are basically kind of global variable or object. Passing and Accessing props. We can pass props to any component as we declare attributes for any HTML tag

Sometimes we might want to update the component manually. This can be achieved using the forceUpdate() method.
examle of ecommrece where we remove from the cart and the data gets deleted from localstorage but component is not updated and we still see the data in page and when we refresh the page then it goes so we forceupadet so that page refresh and data remove from page also


Mounting-:When a component is mounted it means that it's render reprsetaion(html) is inserted into dom
(into index.js root )
componentWillMount() lifecycle hook is primarily used to implement server-side logic before the actual rendering happens, such as making an API call to the server. In this guide, you will learn to use componentWillMount() and make API calls after the initial component rendering.

The <Switch /> component will only render the first route that matches/includes the path. Once it finds the first route that matches the path, it will not look for any other matches. Not only that, it allows for nested routes to work properly, which is something that <Router /> will not be able to handle

https://medium.com/wesionary-team/react-functional-components-vs-class-components-86a2d2821a22
func vs class comp
