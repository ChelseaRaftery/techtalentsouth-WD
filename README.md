# Intro to Web Design

## Naming your files
- Always use lowercase
- Don't use spaces
- If you need a space, add a - like-this.HTML
- For the "homepage" file, call it `index.html`
- At the end of your filename, include the file type. Example `file.html` of `file.css`


## Head
- The head tag is for information that the browser needs to help Google Search, and Social Media share previews.
``` HTML
<head>
    <title> My First Website</title>
    <meta name="description"
    content="Some quick description about my website. 150-160 characters long" />
    <meta charset="UTF-8"/>
  </head>
  ```
  - **Title**: Title of the page, used in Google Search
  - **Meta description**: Used in Google Search preview text and social share text
  - **Charset**: Tells the browser about special characters like quotes, copyrights symbols, and non- English letters.

## Body
- The `<body>` tag is all of our content that is visible on the page.

## Headlines H1 - H6
- Headlines are topics of your page.
- H1 is the primary topic
- Each headline is a sub-topic of the previous level

**Example:**
```html
<body>
    <h1>My First Website: Planet Earth</h1>
    <h2>North America</h2>
    <h3>United States</h3>
    <h4>North Carolina</h4>
    <h5>Raleigh</h5>
    <h6>HQ Raleigh, 310 S. Harrington St. </h6>
</body>
```

## Main
- The `<main>` tag tells Google where the main content is located for SEO

## Paragraphs and styles
- `<p>`is for paragraph
- `<strong` is bold
- `<em>` is italic
- `<u>` is underline

## Ordered Lists and Unordered Lists
- `<ul>` is for an unordered list of bulleted items
- `<ol>` is a numbered list of items

```html
<ul>
    <li>Coding</li>
    <li>Hiking</li>
    <li>puns</li>
</ul>
<ol>
    <li>Gather the ingredients </li>
    <li>Mix the ingredients </li>
    <li>Bake the ingredients at 300 degrees for 35 miutes</li>
    <li>Let the cake chill and serve</li>
</ol>
```
