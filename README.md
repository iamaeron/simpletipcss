# SimpleTip CSS

A no-JS, lightweight, customizable, and easy-to-use tooltip.


## Installation
Include simpletipcss to your project quickly using a package manager, or a cdn link.

### Package manager

with npm:
```
npm install simpletipcss
```

with yarn:
```
yarn add simpletipcss
```

then import it:

```js
import 'simpletipcss/simpletip.css'
```

### CDN link

with unpkg:
```html
<link
  rel="stylesheet"
  href="https://unpkg.com/simpletipcss@0.0.4/simpletip.css"
/>
```

with jsDelivr:
```html
<link 
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/simpletipcss@0.0.4/simpletip.css"
/>
```

## Usage

SimpleTip is very easy to use:

```html
<div data-simpletip="This is the tooltip content" class="simpletip-right">
  You should see a tooltip in the right when you hover here.
</div>
```

## Customizing
You can customize SimpleTip by creating a new CSS file and overriding the variables.

```css
/* override.css */
:root {
  /* Changing background color  */
  --simpletip-bg: #5D5D77;

  /* Changing text color  */
  --simpletip-text: #fff;

  /* Changing border-radius  */
  --simpletip-radius: 4px;
}
```

and then import that file after the `simpletip.css`:

### JS
```js
import 'simpletipcss/simpletip.css'
import './css/override.css'
````

### HTML
```html
<link 
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/simpletipcss@0.0.4/simpletip.css"
/>
<link
  rel="stylesheet"
  href="./css/override.css"
/>
```

## Default Variables

```css
:root {
  /* Background Color  */
  --simpletip-bg: #5D5D77;

  /* Text Color  */
  --simpletip-text: #fff;

  /* Tooltip's margin to the item */
  --simpletip-offset: 10px;

  /* Transition, how fast the tooltip will show/hide */
  --simpletip-transition: opacity 200ms ease-in-out;

  /* Font  */
  --simpletip-font: 500 14px "Inter", sans-serif;

  /* Border Radius  */
  --simpletip-radius: 4px;

  /* Padding  */
  --simpletip-padding: 8px;

  /* Width  */
  --simpletip-width: max-content;

  /* Border */
  --simpletip-border: 1px solid transparent;
}
```

### Support

Leaving this project's repository a star will be much appreciated! <3