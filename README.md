# Frontend Mentor - QR Code Component Solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges are excellent for improving coding skills and building projects that mirror real-world UI components.

---

## Table of contents

- [Overview](#overview)
  - [Project Goal](#project-goal)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Project Structure](#project-structure)
  - [Built With](#built-with)
  - [Responsive Behavior](#responsive-behavior)
  - [What I Learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

### Project Goal

The goal was to create a clean and modern QR code component that is visually appealing and fully responsive across various screen sizes, including mobile and desktop.

### Screenshot

#### **Desktop View**

![Desktop Design](./images/desktop-design.jpg)

#### **Mobile View**

![Mobile Design](./images/mobile-design.jpg)

---

### Links

- **Solution URL**: [GitHub Repository](https://github.com/nabi0l/)

---

## My Process

### Project Structure

Here is the structure of the project:

qr-code-component/ │ ├── images/ │ ├── desktop-design.jpg │ ├── mobile-design.jpg │ └── image-qr-code.png │ ├── index.html ├── style.css └── README.md

- **index.html**: The HTML file that contains the structure of the page.
- **style.css**: The CSS file responsible for the styling and responsiveness.
- **images/**: Folder containing design previews and the QR code image.
- **README.md**: Documentation for the project.

### Built With

- **Semantic HTML5** markup
- **CSS3** for styling
- **Flexbox** for layout
- **Media queries** for responsive design
- **Mobile-first** workflow for scalability

### Responsive Behavior

The design is fully responsive and adapts to various screen sizes:

- **Mobile (375px and below)**: The QR code component shrinks and has adjusted padding for small screens.
- **Desktop (1440px)**: The component remains centered with a fixed maximum width.

Key snippet for responsiveness:

```css
@media screen and (max-width: 375px) {
  .container {
    padding: 15px;
    max-width: 90%;
  }

  h2 {
    font-size: 16px;
  }
}

@media screen and (min-width: 768px) {
  .container {
    max-width: 350px;
    padding: 20px;
  }
}

What I Learned
This challenge allowed me to practice the following:

CSS Flexbox for alignment:
Flexbox was used to center the QR code component both vertically and horizontally.
css
Copy code
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: hsl(212, 45%, 89%);
}
Media Queries for responsiveness:

Ensuring the component adjusts seamlessly for mobile and desktop views.
CSS Best Practices:

Using box-shadow, rounded corners, and consistent spacing to create a visually appealing design.


Acknowledgments
Special thanks to Frontend Mentor for providing high-quality challenges. This challenge gave me the opportunity to improve my responsive design skills and enhance my understanding of Flexbox.

If you're looking to practice or sharpen your frontend skills, I highly recommend working on similar challenges on Frontend Mentor.
```
