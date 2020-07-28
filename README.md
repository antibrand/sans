# sans

A variable sans-serif font

![cover image](https://raw.githubusercontent.com/antibrand/sans/master/cover.jpg)

## Variable

The variable version has adjustable weight.

### Variable Weight

Weight available from `100` to `900`.

## Variable Example

Check for font-variation-settings support.

```scss
h1 {
    font-family: 'sans', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', Helvetica, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';

    // Set font weight as bold.
    font-weight: 700;
}

    // Make slightly bolder than bold.
    @supports( font-variation-settings: wght ) {
        h1 {
            font-variation-settings: 'wght' 735;
        }
    }
```

## Static

The static versions are as follows.

### Static Styles

Two styles are available for each of the static weights.

`normal, italic`

### Static Weights

Nine weights available for each of the static styles.

`100, 200, 300, 400, 500, 600, 700, 800, 900`
`thin, extra-light, light, regular, medium, semi-bold, bold, extra-bold, black`
