# GoIT Markup Homework #2: CSS Styling

## Description of the Assignment

This repository contains the solution for GoIT Markup Homework #2. The primary goal was to take the semantic HTML structure from Homework #1 and apply all necessary CSS styling based on the "WebStudio" design layout.

This assignment involved creating and linking an external stylesheet, implementing the correct color palette, setting up custom typography using Google Fonts, and styling all existing elements. A new "Our Portfolio" section was also added to the HTML markup and styled accordingly.

---

## 🎨 Key Styling & Features

The following key features and styling rules were implemented:

### Project & File Structure

* A new `css/` directory was created to hold the project's stylesheets.
* All styles were written in a single `css/styles.css` file and linked in the `<head>` of `index.html`.
* **Modern Normalize** was connected before the main styles to ensure cross-browser consistency.

### Global Styles & Fonts

* **Google Fonts:** Linked the required project fonts from Google Fonts:
    * **Roboto** (weights 400, 500, 700)
    * **Raleway** (weight 700)
* **Body Styles:** Set global styles on the `<body>` element:
    * `font-family: "Roboto", sans-serif` as the default font.
    * `color: #434455` as the default text color.
    * `background-color: #FFFFFF` as the page background.
* **Resets:** Basic resets were applied to remove default link underlines (`text-decoration: none`) and list markers (`list-style: none`).

### Header & Navigation

* **Logo:** Styled using the **`Raleway`** font, set to `uppercase`, and given the brand colors (`#4d5ae5` for "Web" and `#2e2f42` for "Studio").
* **Navigation Links:** Styled with `font-weight: 500` and a base color of `#2e2f42`.
* **Contact Info (`<address>`):** The `font-style: normal` property was applied to the `<address>` tag to remove default italics.
* **Hover/Focus States:** All interactive links in the header (navigation and contacts) change `color` to **`#404bbf`** on hover and focus.

### Section-Specific Styling

* **Hero (Section 1):**
    * Given a dark background (`#2e2f42`) and white text (`#ffffff`).
    * The `<h1>` title is styled to be large (`56px`), centered, and bold.
    * The "Order Service" button is styled with a blue background (`#4D5AE5`), white text, and `cursor: pointer`. It darkens to `#404BBF` on hover/focus.
* **Features (Section 2):**
    * Section `<h3>` titles (e.g., "Strategy") are styled with `font-weight: 500` and `font-size: 20px`.
* **Our Team (Section 3):**
    * This section has a light gray background (`#F4F4FD`).
    * The section `<h2>` ("Our Team") is centered, capitalized, and sized to `36px`.
    * Individual team member cards (`<li>`) are given a white background (`#FFFFFF`).

### New 'Our Portfolio' Section (Section 4)

* The HTML for the "Our Portfolio" section was added to `index.html`, structured as a `<ul>` of projects.
* This section was styled to match the "Our Team" section's `<h2>` (centered, capitalized, `36px`).
* Project items (`<li>`) were styled, with `<h3>` titles and `<p>` descriptions reusing styles from the "Features" section for consistency.

### Footer

* The `<footer>` is styled with the same dark background as the hero (`#2e2f42`).
* The footer logo's "Studio" `<span>` is styled with a white color (`#f4f4fd`).
* The footer description text is also set to a light color (`#F4F4FD`).

---

## 🚀 Live Page

The project is hosted on GitHub Pages. You can view the live result here:

**[https://idziamko.github.io/goit-markup-hw-02/]**
