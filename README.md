# Isolated Bootstrap
If you decided to use Bootstrap in several places of your site but including Bootstrap CSS rewrites your styles in other places you should use these CSS files to isolate Bootstrap CSS.

## Usage

1. Replace the normal Bootstrap link with one of these in the head of a HTML page.

For Bootstrap 3:
```html
<link rel="stylesheet" href="versions/3.3.7/iso_bootstrap3.3.7.css" />
```
  For Bootstrap 4:
```html
<link rel="stylesheet" href="versions/4.0.0/iso_bootstrap4.0.0.css" />
```

  For Bootstrap 5:
```html
<link rel="stylesheet" href="versions/5.0.2/iso_bootstrap5.0.2.css" />
```

2. Create `div` element with `class="bootstrap<version>"` where you want to use Bootstrap styles.
3. It's ready to use:
```html
<!-- there Bootstrap doesn't work -->
<div class="bootstrap3">
    <!-- there Bootstrap 3 works-->
</div>
<!-- there Bootstrap doesn't work-->

<!-- there Bootstrap doesn't work -->
<div class="bootstrap4">
    <!-- there Bootstrap 4 works-->
</div>

<!-- there Bootstrap doesn't work-->

<!-- there Bootstrap doesn't work -->
<div class="bootstrap5">
    <!-- there Bootstrap 5 works-->
</div>
<!-- there Bootstrap doesn't work-->
```
Demo:
https://zakk616.github.io/Isolated-Bootstrap/
