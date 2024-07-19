link to source folder:

/c/Users/glads/Downloads/props-render-a-components-props

link to codecademy lesson:

https://www.codecademy.com/courses/react-101/lessons/this-props/exercises/render-component-props

link to AI:

https://chatgpt.com/c/14426d70-9262-425d-95e0-ff40af8c4e99


### PROPS

**Render a Component's props**

Props allow us to customize the component by passing it information.

We’ve learned how to pass information to a component’s props object. You will often want a component to display the information that you pass.

To make sure that a function component can use the props object, define your function component with props as the parameter:
```
function Button(props) {
  return <button>{props.displayText}</button>;
}
```
In the example, props is accepted as a parameter, and the object values are accessed with the dot notation accessors pattern (object.propertyName).

Alternatively, since props is an object, you can also use destructuring syntax like so:
```
function Button({displayText}) {
  return <button>{displayText}</button>;
}

```

### Instructions

Checkpoint 1 Passed

1. Explore the code in the code editor.

Product.js contains the outline of a component responsible for displaying the products of an e-commerce site.

App.js contains the top-level App component, which calls the Product component with three pieces of information: name, price, and rating.

However, the Product component does not accept props.

In Product.js, modify the Product component so that it accepts props in the function definition.

In the line that defines the function, include props as a parameter.

For example, a Card component that accepts props looks like this:

function Card(props) {

}

Checkpoint 2 Passed
2. Next, display the name of the product in the <h1></h1> tag by injecting the name value from props.

Hint

The syntax to extract a property from the props object is:

props.nameOfProp

Make sure to put it between the <h1> tags!

Checkpoint 3 Passed

3. For the <h2></h2> tag, inject the price value from props.

Hint

The syntax to extract a property from the props object is:

props.nameOfProp

Make sure to put it between the <h2> tags!

Checkpoint 4 Passed

4. Finish it off by injecting the rating value from props within the <h3></h3> tags.

Hint

The syntax to extract a property from the props object is:

props.nameOfProp

Make sure to put it between the <h3> tags!

Checkpoint 5 Passed

5. In App.js, test out your code by tweaking the value of name, price, and rating.

Click Run. Once the browser refreshes, new information about a product should appear on the screen.

