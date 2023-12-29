# `🫙` clsls

> classless framework for fast prototyping

-   `0` classes
-   `0` dependencies
-   use plain HTML tags to get pleasant look
-   combine tags to get more complex components
-   customize colors and decorations easily
-   auto enabling dark `||` light theme based on system preferences

## Demos

- [Main](https://clsls.github.io/framework/) with docs by innspecting source code `🗿`

## Install

For last version:

```html
<link href="https://clsls.github.io/framework/src/index.css" rel="stylesheet" />
```

## Customize

To create your own theme just rewrite following variables in your CSS file:

```css
{
    /* colors */
    --clsls-color-main: ;
    --clsls-color-opposite: ;
    --clsls-color-background: ;
    --clsls-color-text: ;
    --clsls-color-link-hover: ;
    --clsls-color-button: ;
    --clsls-color-border: ;
    --clsls-color-code: ;
    /* fonts */
    --clsls-font-heading: ;
    --clsls-font-text: ;
    /* other */
    --clsls-line-thickness: ;
    --clsls-radius: ;
    --clsls-zoom-main: ;
    --clsls-icon-chevron: ;
}
```

## Roadmaps

### v2

- [x] code block
- [x] seprate font for headline
- [ ] card component
- [ ] dotted link
- [ ] sizes for buttons
- [ ] more demos
- [ ] checkboxes
- [ ] npm install support
- [ ] better docs page with code to copy

### v3

- [ ] match variable name with CSS properties and HTML tags
    - [ ] `--clsls-color-link-hover` →
    - [ ] `--clsls-radius` → `--clsls-border-radius`
    - [ ] `--clsls-line-thickness` → `--clsls-border-width`
    - [ ] `--clsls-color-code` → `--clsls-color-code-background`
- [ ] deletion of `--clsls-zoom-main`?