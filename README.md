# Turp
The lean CSS framework

## Layout
```css
.container - This is your generic container, use it
```
```css
.vertical - Aligns items vertically
```
```css
.start .end .center - Alignment of the items in the direction of the flex
```
```css
.items-start .items-end .items-center - Alignment of the items in the opposite direction of the flex
```
```css
.spaced .spaced-evenly - Relative placement of the items
```
```css
.tile5 - Align items like a tile with 5 columns
```
```css
.w20 - Width: 20%
```
```css
.h20 - Height: 20%
```
```css
.off20 - Margin-left: 20px
```
```css
.flex20 - Flex: 20
```

```html
<div class="container sm-flex xs-tile5"> <!-- Use tile alignment at xs, flex at sm and above sizes -->
  <div class="sm-w33 p5">1</div> <!-- Width: 33% for sm and above -->
</div>
```

## Utils
```css
.t-left .t-center .t-right - Text alignment
```
```css
.t-sans-serif .t-serif - Font type
```
```css
.t-italic .t-light .t-bold .t-black .t-linethrough .t-underline .t-small - Text specs
```
```css
.t3 .h3 h3 - Use font size 3 (1-6)
```
```css
.mb5 .pt3 .bb10 - Respectively margin-bottom, padding-top, border-bottom (1-10)
```
```css
.b-radius20 - Border-radius: 20px (0-50)
```
