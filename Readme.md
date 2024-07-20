# Munnar Tourism Website

## Overview

This project is a simple HTML website that highlights the tourist attractions in Munnar, Kerala. The website includes various sections such as Home, About Places, Images, Packages, Map, and Contact. It features an interactive map of Munnar with clickable areas.

## Features

- **Home Page:** Introduction to Munnar Tourism.
- **Interactive Map:** Highlights important locations in Munnar with clickable links.
- **Contact Information:** Provides contact details for further inquiries.

## Files

- `index.html`: The home page of the website.
- `styles.css`: The external CSS file for styling the website.
- `munnar travel map.jpg`: The image used in the interactive map.
- `munnar.html`: The page linked from the Munnar area on the map.
- `silent.html`: The page linked from the Silent Valley area on the map.

## How to Use

1. Clone the repository to your local machine using:
   ```sh
   git clone <repository_url>
   ```
2. Open `index.html` in your web browser to view the home page.
3. Navigate through the different sections using the navigation links provided.
4. Click on the areas in the interactive map to view more details about Munnar and Silent Valley.

## HTML Structure

### `index.html`

- **DOCTYPE Declaration:** Specifies the HTML5 document type.
- **Meta Tags:** Defines the character set and viewport settings.
- **Link to CSS:** Links to the external `styles.css` file for styling.
- **Table Layout:** Uses a table to organize the content.
- **Interactive Image Map:** Provides clickable areas on the map image that link to different pages.
- **Contact Information:** Includes contact details at the bottom of the page.

### `styles.css`

- **Body Styling:** Sets the font, background color, and removes default margins and padding.
- **Table Styling:** Adds background color, shadow, and spacing to the table.
- **Link Styling:** Styles the navigation links with hover effects.
- **Image Hover Effect:** Adds a zoom-in effect when hovering over the images.
- **Text Styling:** Styles the headings and other text elements.

## Example of an Image Map in `index.html`

```html
<img src="munnar travel map.jpg" usemap="#image-map" />

<map name="image-map">
  <area
    target="_parent"
    alt="Munnar"
    title="Munnar"
    href="munnar.html"
    coords="292,97,298,101"
    shape="rect"
  />
  <area
    target="_parent"
    alt="Silent valley"
    title="Silent valley"
    href="silent.html"
    coords="339,246,342,240"
    shape="rect"
  />
</map>
```
