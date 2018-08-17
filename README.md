![react-progress-arc](https://cloud.githubusercontent.com/assets/316538/11975797/be322a88-a971-11e5-9719-adcbf2a93cca.png)

Simple circular progress meters for React.js, rendered in SVG.

Installation
============

```
npm install --save react-progress-arc
```

Usage Examples
==============

Basic usage:

```javascript
import React from 'react';
import ReactDOM from 'react-dom';
import ProgressArc from 'react-progress-arc';

const container = document.createElement('div');
document.getElementsByTagName('body')[0].appendChild(container);

ReactDOM.render(<ProgressArc completed={0.5} />, container);
```

Customisation
=============

The following properties can be set to customise the arcs through React:

+ `completed` - Set this to a value between 0 and 1. You probably want this bound to `this.state.something`.
+ `stroke` - Progress meter colour, default `#444`.
+ `diameter` - External diameter, width and height of the arc, default `50`.
+ `background` - Colour of the background circle, default `transparent`.
+ `strokeWidth` - Thickness of the arc drawn, default `5`.

License
=======
MIT
