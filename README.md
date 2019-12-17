# obss

[![npm version](https://badge.fury.io/js/obss.svg)](https://badge.fury.io/js/obss)

A package for Object Based StyleS in css-in-js.

```
import { css, styled } from 'obss';

const titleClass = css({
  color: 'red'
})

// <h2 className={titleClass}>hello world</h2>

const Div = styled('div', {
  padding: '20px',
  'font-size': p => p.size || '20px',
}));

// <Div size={'32px'} />
```
