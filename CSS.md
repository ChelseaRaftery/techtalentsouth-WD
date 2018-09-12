# css

## CSS Tags
``` CSS
  tag{
    property-name: value;
  }
  ```

## CSS File
  Name your file `filename.css`

  ## Link the HTML <> CSS
  ```html
    <link rel="stylesheet" href="folder/folder/filename.css" type="text/css" />
    ```
## Colors
```CSS
body{
  /* Background Colors  */
  background-color: lightblue;
  /* RGBA is Red, Green, Blue, alpha (transparency) */
  background-color: rgba(255, 0, 0, .5);
  background-color: black;

/* Text color with a word */
  color: darkblue;
/*  Text color with a HEX Code */
/* Hex Code is create with red, blue, green #RRGGBB */
/* Hex numbers are 0-15 represented by 1-9,a-f  */
  color: #ffffff;
  color: #000000;
  color: rgba(0, 255, 0, 0.5);
  /* Hexcodes can also have an alpha value. #RRGGBBAA */
  color: #00ff00ff

}
```

## Background images
```css
tag {
  /* This is a background image that repeats (pattern) */
  background-image: url("images/back.png");

  /* Post a remote image */
  background-image: url("https://upload.wikimedia.org/wikipedia/commons/5/58/Sunset_2007-1.jpg");
  background-size: 200px;

  /* Cover means to cover the entire page with the image - may stretch */
  background-size: cover;
  /* Contain means show the full image */
  background-size: contain;

  background-repeat: no-repeat;
  background-position: top right;

}
```

## Fonts
```css
@import https://fonts.google.com/

font-size: 35px;
/* em equlas current font siz e- dynamic  */
line-height: 2em;
text-align: center;
text-align: right;
font-family: "Helvetica", "Arial", sans-serif;

}
```
