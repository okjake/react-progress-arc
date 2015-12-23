react-progress-arc
==================

Simple circular progress meters for React.js, rendered in SVG.

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:113.09733552923255;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:100.53096491487338;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:87.96459430051421;;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:75.39822368615503;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:62.83185307179586;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:50.26548245743669;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:37.699111843077524;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:25.132741228718338;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:12.566370614359169;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>

<svg width="50" height="50"><circle cx="25" cy="25" r="20" fill="none" stroke="#444" stroke-width="5" stroke-dasharray="125.66370614359172" style="stroke-dashoffset:0;transform-origin:center center;transform:rotate(-90deg);display: inline-block;"></circle></svg>


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
