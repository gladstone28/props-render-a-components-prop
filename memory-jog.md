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
