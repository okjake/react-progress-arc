![react-progress-arc](https://cloud.githubusercontent.com/assets/316538/11975555/971b03cc-a96f-11e5-939a-1e01ea5132dd.png)

Simple circular progress meters for React.js, rendered in SVG.

Installation
============

```
npm install --save react-progress-arc
```

Usage Examples
==============

Basic usage:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';
import ProgressArc from 'react-progress-arc';

ReactDOM.render(<ProgressArc completed={0.5} />, document.getElementById('container'));
```

Customisation
=============

The following properties can be set to customise the arcs through React:

+ `completed` - Set this to a value between 0 and 1. You probably want this bound to `this.state.something`.
+ `stroke` - Progress meter colour, default `#444`.
+ `diameter` - External diameter, width and height of the arc, default `50`.
+ `background` - Colour of the background circle, default `transparent`.
+ `strokeWidth` - Thickness of the arc drawn, default `5`.

In addition, the arcs can be styled through CSS:

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
