---
published: true
tags:
  - react-js
  - react-native
  - web
  - js
---
```
$ create-react-app [app-name]
```

```
$ npm start
```

Write in HTML

```html
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<div id="root"></div>
```


Write in ReactJS

```jsx
class App extends React.Component {
  constructor(props) {
    super(props);
    
    this.state = {
      
    };
  }

  render() {
  	return (
    
    
    );
  }
}

//export default App;
ReactDOM.render(
  <App />,
  document.getElementById("root")
);
```
