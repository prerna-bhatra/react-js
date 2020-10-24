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
