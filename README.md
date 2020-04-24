# Little React Tooltip

> This is just a tini-tiny Tooltip library, with a simple way to use it, it doesn't currently have a lot of features, but it is certainly a pleasure package to work with.

[![NPM](https://img.shields.io/npm/v/little-react-tooltip.svg)](https://www.npmjs.com/package/little-react-tooltip) [![JavaScript Style Guide](https://img.shields.io/badge/code%20style-airbnb-blue)](https://github.com/airbnb/javascript)

## Install

```bash
npm install --save little-react-tooltip
```

## Usage

```tsx
import React from 'react';

import Tooltip from 'little-react-tooltip';

const Example: React.FC = () =>  {
  return (
    <Tooltip 
      tooltipText="Hey, this is a tooltip!"
    >
      <p>Hover me!</p>
    </Tooltip>
  )
}
```
**NOTE:** the children object of the tooltip NEEDS to be a React Element or a HTML Element, you can't just pass a normal text.

## API
### Props
If a prop is **Required**, the `default` field will appear empty.
name | type | default 
--- | --- | --- 
tooltipText | string | --
size | string | medium
position | string | top
colors | object: font, background | font: black, background: white
children | ReactElement or HTMLElement | --

## License

MIT © [Bruno De Masi](https://github.com/brunodmsi)
