react-progressarc
=================

Simple circular progress meters for React.js.

Installation
============

```
npm install --save react-progressarc
```

Usage Example
=============

```jsx

var React = require('react');
var ReactDOM = require('react-dom');
var ProgressArc = require('react-progressArc');

var App = React.createClass({
  render: function() {
    return <ProgressArc completed={0.5} />
  }
});

ReactDOM.render(<App />, document.getElementById('container'));
```

Customisation
=============

The following properties can be set to customise the arcs through React:

+ `completed` - Set this to a value between 0 and 1. You probably want this bound to `this.state.something`.
+ `stroke` - Progress meter colour, default `'#444'`.
+ `diameter` - External diameter, width and height of the arc, default `50`.
+ `background` - Colour of the background circle, default `transparent`.
+ `strokeWidth` - Thickness of the arc drawn, default `5`.

In addition, the arcs and be styled through CSS:

```css
.progress-arc--bg {
  stroke: #000000
}

.progress-arc--fg {
  transition: all 0.2s;
  stroke: #FF3333;
}
```

License
=======
MIT
