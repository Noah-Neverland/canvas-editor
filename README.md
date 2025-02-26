<h1 align="center">rich-editor</h1>

## Basic usage

```bash
npm i @noahhp/rich-editor --save
```

```html
<div class="rich-editor"></div>
```

```javascript
import Editor from '@noahhp/rich-editor'

new Editor(document.querySelector('.rich-editor'), {
  main: [
    {
      value: 'Hello World'
    }
  ]
})
```

## Install

`yarn`

## Dev

`npm run dev`

## Build

#### app

`npm run build`

#### lib

`npm run lib`
