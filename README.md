# CSS Stories

CSS Stories (CSSS) is a lightweight collection of pure CSS classes to easily define *one-page* layouts for *Scrollytelling* and similiar use cases.

## How to Use

Include a link to the stylesheet (`csss.css`) in your `<head>` tag.

For example:

```html
<link rel="stylesheet" href="csss.css" />
```

## Documentation

- All stories are block elements with a smooth scroll behaviour and (block) snapping of its children enabled.
- All direct children of stories snap to their start position.

### story-horizontal

- Horizontal stories don't wrap their elements.
- All children in horizontal stories are displayed as blocks and have a width of 100%.

Example:

```html
<div class="story-horizontal">
    <!-- story sections here -->
</div>
```

### story-vertical

- Vertical stories do wrap their elements normal.
- All children in vertical stories are displayed as blocks and have a height of 100%.

Example:

```html
<div class="story-vertical">
    <!-- story sections here -->
</div>
```

### -hidden (Scrollbars)

Stories with the -hidden suffix don't show their scrollbars.

Examples:

```html
<div class="story-horizontal-hidden">
    <!-- story sections here -->
</div>
```

```html
<div class="story-vertical-hidden">
    <!-- story sections here -->
</div>
```

### -disabled (Scrollbars)

Stories with the -disabled suffix don't show their scrollbars nor do they allow scrolling (e.g. with mouswheel).

Examples:

```html
<div class="story-horizontal-disabled">
    <!-- story sections here -->
</div>
```

```html
<div class="story-vertical-disabled">
    <!-- story sections here -->
</div>
```

## Demo

Check out the [CSS Stories Demo](https://web-utilz.gitlab.io/csss) page to get an idea of how CSSS can be used (you can view the source directly in your browser or in the repository right [here](https://gitlab.com/web-utilz/csss/-/blob/master/demo/public/index.html)).
