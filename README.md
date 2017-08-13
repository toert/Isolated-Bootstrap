# Isolated Bootstrap
If you decided to use Bootstrap in several places of your site but including Bootstrap CSS rewrites your styles in other places you should use these CSS files to isolate Bootstrap CSS.

## Usage

1. Replace the normal Bootstrap link with one of these in the head of a HTML page.
For Bootstrap 3:
```html
<link rel="stylesheet" href="https://toert.github.io/Isolated-Bootstrap/versions/iso_bootstrap3.3.7.css">
```
For Bootstrap 4:
```html
<link rel="stylesheet" href="https://toert.github.io/Isolated-Bootstrap/versions/iso_bootstrap4.0.6.css">
```
2. Create `div` element with `class="bootstrap"` where you want to use Bootstrap styles.
3. It's ready to use:
```html
<!-- there Bootstrap doesn't work -->
<div class="bootstrap">
    <!-- there Bootstrap works-->
</div>
<!-- there Bootstrap doesn't work-->
```
