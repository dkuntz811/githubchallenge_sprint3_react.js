# githubchallenge_sprint3 React.js

###React.js is JS library for building UI's. It is sometimes called the V in Model, View, Controller. 
It was developed to be used in applications with large amounts of data that change over time (think Facebook). 
React uses components (component-based architecture)
-If a component gets too complex, smaller, simpler components can be created. 

..1. Components
......*Components are used to create a virtual DOM
......*This allows the application to be fast
......*Using the render() function will create a virtual div or other html element
......*That same render() component can be used later to update the same element with different info. ==fast

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>React.js Hello World</title>
		<script src="../vendors/react.js"></script>
		<script src="../vendors/react-dom.js"></script>
		<script src="../scripts/components.js"></script>
	</head>
	<body>
		<h1>React.js Hello World Below</h1>
		<div id="HelloWorld">

		</div>
		<script src="../vendors/react.js"></script>
		<script src="../vendors/react-dom.js"></script>
		<script src="../scripts/components.js"></script>
	</body>
</html>
```

```javascript
ReactDOM.render(
  React.DOM.div(null, "Hello React World!"),
  document.getElementById("HelloWorld")
);
```
