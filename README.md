# Vite SVG Sprite Plugin

### Install
```bash
yarn add vite-svg-loader
or 
npm install vite-svg-loader --save-dev 
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
svgstore('your-svg-path')
```

