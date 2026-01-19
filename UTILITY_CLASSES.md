# Bootstrap-like Utility Classes Reference

This site includes Bootstrap-like utility classes that **won't interfere** with the Jekyll theme's default styles.

## Quick Examples

```html
<!-- Centered text with bold font -->
<p class="text-center fw-bold">Centered Bold Text</p>

<!-- Flexbox layout with gap -->
<div class="d-flex justify-content-between align-items-center gap-3">
  <span>Item 1</span>
  <span>Item 2</span>
</div>

<!-- Margin and padding -->
<div class="mt-4 mb-3 px-5">Content with spacing</div>
```

## Available Utility Classes

### Spacing (Margin & Padding)

Scale: `0` = 0, `1` = 0.25rem, `2` = 0.5rem, `3` = 1rem, `4` = 1.5rem, `5` = 3rem

#### Margin
- `m-{0-5}` - all sides
- `mt-{0-5}` - top
- `mb-{0-5}` - bottom
- `ml-{0-5}` - left
- `mr-{0-5}` - right
- `mx-{0-5}` - left & right
- `my-{0-5}` - top & bottom
- `mx-auto` - center horizontally

#### Padding
- `p-{0-5}` - all sides
- `pt-{0-5}` - top
- `pb-{0-5}` - bottom
- `pl-{0-5}` - left
- `pr-{0-5}` - right
- `px-{0-5}` - left & right
- `py-{0-5}` - top & bottom

### Text

#### Alignment
- `text-left`
- `text-center`
- `text-right`
- `text-justify`

#### Font Weight
- `fw-light` (300)
- `fw-normal` (400)
- `fw-medium` (500)
- `fw-semibold` (600)
- `fw-bold` (700)
- `fw-bolder`

#### Font Style
- `fst-italic`
- `fst-normal`

#### Transform
- `text-lowercase`
- `text-uppercase`
- `text-capitalize`

#### Decoration
- `text-decoration-none`
- `text-decoration-underline`
- `text-decoration-line-through`

### Display

- `d-none`
- `d-inline`
- `d-inline-block`
- `d-block`
- `d-flex`
- `d-inline-flex`
- `d-grid`

### Flexbox

#### Direction
- `flex-row`
- `flex-column`
- `flex-row-reverse`
- `flex-column-reverse`

#### Wrap
- `flex-wrap`
- `flex-nowrap`
- `flex-wrap-reverse`

#### Justify Content
- `justify-content-start`
- `justify-content-end`
- `justify-content-center`
- `justify-content-between`
- `justify-content-around`
- `justify-content-evenly`

#### Align Items
- `align-items-start`
- `align-items-end`
- `align-items-center`
- `align-items-baseline`
- `align-items-stretch`

#### Align Self
- `align-self-auto`
- `align-self-start`
- `align-self-end`
- `align-self-center`
- `align-self-baseline`
- `align-self-stretch`

#### Gap
- `gap-{0-5}`

### Sizing

#### Width
- `w-25` (25%)
- `w-50` (50%)
- `w-75` (75%)
- `w-100` (100%)
- `w-auto`

#### Height
- `h-25` (25%)
- `h-50` (50%)
- `h-75` (75%)
- `h-100` (100%)
- `h-auto`

#### Max Width/Height
- `mw-100` (max-width: 100%)
- `mh-100` (max-height: 100%)

### Position

- `position-static`
- `position-relative`
- `position-absolute`
- `position-fixed`
- `position-sticky`

### Overflow

- `overflow-auto`
- `overflow-hidden`
- `overflow-visible`
- `overflow-scroll`

### Visibility

- `visible`
- `invisible`

## Custom Project Classes

### Badge Container
```html
<div class="badge-container">
  <img src="badge1.svg" alt="badge">
  <img src="badge2.svg" alt="badge">
</div>
```

## Adding More Utilities

To add more utilities, edit `/assets/css/custom.css` and add your classes there. All utilities use `!important` to ensure they override other styles when needed.
