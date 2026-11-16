# Chatter Landing Page

**AI-Powered FullStack Karatu 2026 – First Semester Project Exam**

A responsive landing page for **Chatter**, a platform for text-based content where writers and readers connect. Built from a Figma design using plain HTML and CSS, with no frameworks and no JavaScript.

## About This Project

This project was submitted as the First Semester Project Exam for the AI-Powered FullStack Karatu 2026 programme. The task was to convert the provided <a href = "https://www.figma.com/design/TXzuoMAwGEIfWcAq0HbBNY/purposed?node-id=52-40&t=EKqFrOjPzGFObnGr-0">Figma design</a> into a responsive web page using HTML and CSS.
## Features

- Built from the "Landing page" frame of the Figma design (1440px desktop layout)
- Fully responsive: desktop, tablet and mobile layouts
- CSS-only hamburger menu on smaller screens (no JavaScript)
- Full-width hero, testimonial and footer sections
- Design tokens (colours, font, spacing) stored as CSS custom properties
- Semantic HTML with accessible labels and alt text

## Page Sections

1. **Header** – logo, navigation links, Log in and Sign up buttons
2. **Hero** – headline, tagline and call-to-action over a background image
3. **About Chatter** – description of the platform with an image
4. **Why you should join chatter** – three feature cards: Analytics, Social interactions, Content creation
5. **Testimonial** – user quote with portrait
6. **Call to action** – "Write, read and connect with great minds on chatter"
7. **Footer** – Explore, Support and Official blog links

## Built With

- HTML5
- CSS3 (Flexbox, Grid, custom properties, media queries)
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) from Google Fonts
- [Font Awesome 6](https://fontawesome.com/) icons via CDN

## Project Structure

```
chatter/
├── index.html
├── style.css
├── README.md
└── assets/
    ├── hero.png.jpg
    ├── about.png.jpg
    ├── testimonial.png.jpg
    ├── member-1.png.jpg
    ├── member-2.png.jpg
    └── member-3.png.jpg
```

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/lionabiola-bit/chatter.git
   ```

2. Open the project folder and double-click `index.html`, or open it with the Live Server extension in VS Code.

No build step or installation is needed. An internet connection is required for the font and icons to load.

## Responsive Breakpoints

| Breakpoint | Target        | Layout changes                                             |
|------------|---------------|------------------------------------------------------------|
| ≤ 1200px   | Small laptops | Reduced page padding, flexible card widths, scaled images  |
| ≤ 900px    | Tablets       | Sections stack vertically, navigation becomes a hamburger menu |
| ≤ 560px    | Phones        | Smaller text and padding, single-column footer             |

## Design Tokens

| Token            | Value     | Use                     |
|------------------|-----------|-------------------------|
| `--blue-500`     | `#543EE0` | Brand colour, buttons   |
| `--black-700`    | `#111111` | Headings and body text  |
| `--black-400`    | `#626262` | Card body text          |
| `--cream`        | `#FFF6E5` | Testimonial and footer background |
| Font             | DM Sans   | 400, 500, 700           |

## Credits

- Photos from [Unsplash](https://unsplash.com/)
- Icons by [Font Awesome](https://fontawesome.com/)
- Font: DM Sans via [Google Fonts](https://fonts.google.com/)

## Author

**Oyewole Saheed Abiola** – [GitHub](https://github.com/lionabiola-bit)
