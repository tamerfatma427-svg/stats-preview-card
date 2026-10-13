# Stats Preview Card

A responsive stats preview card component built as a solution for the [Frontend Mentor](https://www.frontendmentor.io) challenge.

## Live Demo

[View the live site](https://tamerfatma427-svg.github.io/stats-preview-card/)

## Overview

The goal of this project is to recreate the design of a stats card as closely as possible, with a dark theme, a purple-tinted image, and a row of key statistics.

Features:

- Two-column card layout (content + image)
- Purple overlay on the image using `mix-blend-mode`
- Highlighted keyword in the heading
- Three stats displayed in a row

## Built With

- Semantic HTML5
- CSS3 (Flexbox)
- Google Fonts

## Colors

| Usage | HEX |
|---|---|
| Page background | `#090b1a` |
| Card background | `#1d1b3b` |
| Accent (purple) | `#aa5cdb` |
| Highlighted text | `#b65ce8` |
| Paragraph text | `#c5c3d1` |
| Stat labels | `#aaa8bd` |
| White | `#ffffff` |

## Fonts

- **Inter** (400, 700, 800) for headings and body text
- **Lexend Deca** (400) for stat labels

## Project Structure

```
stats-preview-card/
├── index.html
├── style.css
├── image-header-desktop.jpg
└── README.md
```

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/tamerfatma427-svg/stats-preview-card.git
   ```

2. Open the project folder:

   ```bash
   cd stats-preview-card
   ```

3. Open `index.html` in your browser.

No build tools or dependencies are required.

## What I Learned

- Using `mix-blend-mode: multiply` to tint an image with a background color
- Building a two-column layout with Flexbox
- Controlling spacing between items with `gap` instead of `space-between`
- Why heading elements need their own `font-size`, since browser defaults override inherited sizes

## Author

- GitHub: [@tamerfatma427-svg](https://github.com/tamerfatma427-svg)
