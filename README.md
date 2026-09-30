# HealNet

A landing page for **HealNet**, a made-up digital healthcare service. This project is part of a beginner class on **HTML and CSS basics**. Use it to see how a real-looking web page is built, one section at a time.

---

## What you'll learn

By reading and changing this project, you'll practice:

- **HTML structure:** `nav`, `section`, `header`, `form`, headings, paragraphs, images, and lists
- **Forms:** `label`, `input`, placeholders, and buttons
- **CSS basics:** selectors, classes, colors, fonts, spacing, and the `box-sizing` reset
- **Layout with Flexbox:** placing items in rows and columns, spacing, and alignment
- **Centering a page:** using a `.container` with `max-width` and `margin: 0 auto`
- **Gradients:** gradient backgrounds, gradient text, and gradient borders
- **Positioning:** `position: relative`, `position: absolute`, and `z-index` for decorative shapes
- **External resources:** loading a Google Font (Manrope) and icons from Font Awesome

---

## Project structure

```
heal-net/
├── index.html      The page content (HTML)
├── style.css       All the styles (CSS)
├── index.js        JavaScript practice examples (commented out)
└── images/         Pictures, icons, and decorative shapes
```

---

## How to run it

1. **Get the code.** Click the green **Code** button on this page, then **Download ZIP**, and unzip it. If you use Git, you can run:
   ```bash
   git clone https://github.com/Renn90/heal-net.git
   ```
2. **Open the folder in [VS Code](https://code.visualstudio.com/).**
3. **Install the Live Server extension.** Open the Extensions panel (the squares icon on the left), search for **Live Server**, and install it.
4. **Start the page.** Right-click `index.html` and choose **Open with Live Server**. The page opens in your browser, and it refreshes every time you save a file.

> **Why Live Server?** The image paths in this project start with `/` (for example `/images/hero-image.png`). If you double-click `index.html` to open it, the browser can't find the images. Live Server fixes this.

---

## Walk through the page

Open `index.html` and `style.css` side by side, and find each section:

| Section | What to look at in the HTML | What to look at in the CSS |
|---|---|---|
| **Navigation bar** | The `<nav>` with the logo (an SVG), the menu list, and the "Join us" button | `.nav-bar` and `.nav-list` use Flexbox to line things up in a row |
| **Hero** | The big heading, the paragraph, the button, and the hero image | `.hero-section` places the text and image side by side; `.gradient-text` colors the words "trusted partner" |
| **Booking form** | The `<form>` with labels, inputs, and a button | `.gradient-border` creates the light blue border; `.flex-form-items` puts the inputs in a row |
| **Services** | The heading and five service cards with icons | `.service-grid-top` and `.service-grid-bottom` arrange the cards; `.waves-vector-1` and `.waves-vector-2` are decorative shapes placed with `position: absolute` |

**Tip:** right-click any part of the page in your browser and choose **Inspect**. You'll see the HTML and the CSS rules for that element, and you can change values to see what happens.

---

## The JavaScript file

`index.js` has small JavaScript examples that are commented out (each line starts with `//`). They show:

- **Objects:** a `student` with a name, level, CGPA, and department
- **if / else if / else:** checking the student's level and CGPA
- **The ternary operator:** a short way to write an if/else
- **switch:** choosing a message based on the day of the week

To try one, remove the `//` from its lines, save the file, then open the browser's console (press **F12**, or right-click, **Inspect**, then the **Console** tab) to see the output.

---

## Practice exercises

Try these once you're comfortable with the page:

- [ ] Change the menu items in the navigation bar into real links using `<a href="#">`
- [ ] Add hover effects to the buttons and menu links (for example, change the color when the mouse is over them)
- [ ] Change the date field in the form to `type="date"` so it shows a calendar
- [ ] Add a new section, such as "Why choose us" or "Meet our doctors"
- [ ] Add a footer with contact details and links
- [ ] Make the page work on phones using media queries (`@media (max-width: 768px) { ... }`)
- [ ] Move the main colors into CSS variables (for example `--primary: #0095DE;`) and try a new color theme

---

## Helpful resources

- [MDN: HTML basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content)
- [MDN: CSS basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Styling_the_content)
- [CSS-Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flexbox Froggy](https://flexboxfroggy.com): a game for practicing Flexbox
- [web.dev: Learn CSS](https://web.dev/learn/css)
