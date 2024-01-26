# Apology Page

This is a simple apology page created using HTML and CSS, featuring a heartfelt message and animations. You can check out the live demo [here](https://hadep275.github.io/Flip-Text-Animation/).


## Getting Started

To view the apology page, simply open the `index.html` file in your preferred web browser.

```bash
open index.html
```

## Dependencies

This project uses Font Awesome for the heart-crack and sad-tear icons. The necessary CSS file is linked from the Font Awesome CDN.

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" />
```

Make sure you have an internet connection to load the Font Awesome styles.

## Styling

The page has a dark background color (`#000000`) and features a text animation along with a moving box. The text has a shadow effect and a combination of red and orange colors for the heart-crack and sad-tear icons, respectively.

### Text Styling

- Font: Courier New, Courier, monospace
- Font Size: 50px
- Text Shadow: 0px 0px 20px #6b31ff

### Animation

The moving box is animated using CSS keyframes. It starts with a width of 620px and moves from left to right, collapsing to 0px width.

```css
@keyframes move2 {
    from {
        margin-left: -610px;
        width: 620px;
    }
    to {
        margin-left: 0px;
        width: 0px;
    }
}
```

Feel free to customize and modify the styles according to your preferences.

## Author

![hadep275](https://github.com/hadep275)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
