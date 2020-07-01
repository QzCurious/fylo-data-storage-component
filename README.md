Challenge By [Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n)

# Notes

Make a triangle:
```css
/* change one of transparent of border-color to solve the secret */
div {
  width: 0;
  height: 0;
  border-color: #a8cfc2 #a8cfc2 transparent transparent;
  border-width: 30px;
  border-style: solid;
}
```

## [BEM](https://en.bem.info/methodology/quick-start/)

There are different [coding conventions](https://en.bem.info/methodology/naming-convention/) for BEM.

An element is part of a block, not part of another element!
It's not valid for the name `block__elem1__elem2`. [Learn more...](https://en.bem.info/methodology/quick-start/#nesting-1)

## Layout

[Grid for layout, Flexbox for components](https://ishadeed.com/article/grid-layout-flexbox-components/)

## Sass

Instead of use `@import`, use `@use`. [Learn more...](https://sass-lang.com/documentation/at-rules/import)

## Browser

Browsers rounded decimal places (at least for chrome and firefox).
[Browser Rounding and Fractional Pixels](https://cruft.io/posts/percentage-calculations-in-ie/)
