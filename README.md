# Vite SVG Sprite Plugin

### Install
```bash
yarn add vite-svg-sprite-plugin
or 
npm install vite-svg-sprite-plugin
```

### Setup

#### `vite.config.js`
```js
import svgstore from 'vite-svg-sprite-plugin'

export default defineConfig({
  plugins: [vue(), svgstore()]
})
```
### `main.js`
```js
import '@svgstore';
```

### Options
default path is 'src/assets/icons'
```js
svgstore({
  inputFolder: 'src/assets/svgs'
})
```

### Use
```html
<svg>
  <use xlinkHref={'#svgname'}></use>
</svg>
```

