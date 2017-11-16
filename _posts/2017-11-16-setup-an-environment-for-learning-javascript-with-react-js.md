---
published: true
tags:
  - javascript
  - react-js
---
* in **Cmder (for Windows)** or your **Bash (for Linux)** console

```bat
$ create-react-app [any-name: learning-app]
$ cd learning-app
$ npm start
```

* Prepare your browser
* Open a IDE or a text editor
* In the path src/App.js

```javascript
class App extends Component {
	
  learn(field, event) {
    // if you don't pass value to field, it will be 'undefined',
    // but if you don't pass value to 'event', it will still be there
    // type your test code below



    // type your test code above
  }

  render() {
    return (
      <div className="fluid-container">
      	<input onChange={this.learn.bind(this, "name")} className="form-control" type="text" placeholder="Name" /><br />
      </div>
    );
  }
}
```


* **Add code snippet** to the **test code position** as above shown
* **Press *F5* on your keyboard** each time you update and save your code
* Then you can **validate your result with your browser**.

<br />
<br />