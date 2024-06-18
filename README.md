# new-react-canvas-gauges
[![GitHub stars](https://img.shields.io/github/stars/marcuscmy/react-canvas-gauges.svg?style=flat-square)](https://github.com/marcuscmy/react-canvas-gauges/stargazers)
[![npm version](https://img.shields.io/npm/v/new-react-canvas-gauges.svg?style=flat-square)](https://www.npmjs.com/package/new-react-canvas-gauges)
[![npm license](https://img.shields.io/npm/l/new-react-canvas-gauges.svg?style=flat-square)]()
[![npm](https://img.shields.io/npm/dw/new-react-canvas-gauges.svg?style=flat-square)]()
[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

## Introduction
Canvas gauges component is based on [canvas-gauges](https://canvas-gauges.com/) for React.

This repo is forked from 1995parham by Parham Alvani.

I have only updated dependencies to latest package versions.

## Installation
```
npm install react-canvas-gauges --save
```
## Example
```jsx
<RadialGauge
   units='°C'
   title='Temperature'
   value={this.state.temperature}
   minValue={0}
   maxValue={50}
   majorTicks={['0', '5', '15', '20', '25', '30', '35', '40', '45', '50']}
   minorTicks={2}
></RadialGauge>
```
