# Responsive Navigation Menu and Image Gallery

This project showcases a responsive website featuring a modern navigation system and a fully responsive image gallery.

## Project Structure

```
.
├── index.html
├── README.md
└── static
    ├── css
    │   └── style.css
    └── images
        └── background.jpg

```

## Desktop Navigation Design

The desktop navigation features a header with a semi-transparent background and backdrop blur effect. The header remains fixed at the top of the viewport, providing consistent access to navigation elements throughout the user’s browsing experience.

The navigation bar utilizes flexbox layout to achieve optimal spacing between the logo and navigation elements. The “Clínica Vida” logo is positioned on the left side with hover effects that transition to a lighter blue (#4a90e2), while the main navigation links (Home, Services, Doctors, Contact) and the language switcher (PT/EN) positioned on the right side. Each navigation element features smooth hover transitions that enhance user interaction feedback.

## Mobile Navigation Implementation

The mobile navigation system transforms the horizontal layout into a collapsible hamburger menu for screens below 768px. This responsive transformation ensures optimal usability across all device types. The hamburger icon consists of three horizontal bars that animate smoothly when activated, providing clear visual feedback to users.

When the hamburger menu is activated through the checkbox input mechanism, the navigation menu slides down from the top with a translateY transformation. The mobile menu features a semi-transparent background with backdrop blur effects. Navigation links stack vertically with increased padding for touch-friendly interaction.

## Responsive Image Gallery

The project includes a modern, fully responsive image gallery that showcases 20 medical services. The gallery uses CSS Grid (flex grid) to distribute and align images in a visually appealing way.
• On desktop screens, the gallery displays images in 4 columns.
• On tablet screens, it reduces to 2 columns.
• On mobile screens, it displays a single column for optimal readability and usability.

Each gallery item includes a medical service image and a caption. The layout automatically adapts to the screen size, ensuring a consistent and attractive presentation on all devices. The gallery grid and its responsiveness are achieved purely with CSS, without the need for JavaScript

## Features

    •	Responsive Navbar with Hamburger Menu on screens smaller than 768px.
    •	Responsive Image Gallery using CSS Grid with automatic column reduction on smaller screens.
    •	Change color of links and change mouse pointer when hovering over menu items.
    •	Return to the home page by clicking on the “Clínica Vida” logo.
    •	Smooth transitions and visual feedback for navigation and gallery items.

## Images

Main screen - index.html:
![main screen - index.html](<static/images/Captura de ecrã 2025-06-01, às 12.14.04.png>)

link color change on mouseover:
![change link color on mouse hover](<static/images/Captura de ecrã 2025-06-01, às 12.14.28.png>)

Hamburguer menu on screens than 768px:
![hamburguer menu](<static/images/Captura de ecrã 2025-06-01, às 12.18.13.png>)

Menu links when clicking on the hamburger menu:
![menu links in the hamburguer menu](<static/images/Captura de ecrã 2025-06-01, às 12.18.26.png>)

Gallery grid on desktop:
![Full page on desktop](<static/images/Captura de ecrã 2025-06-17, às 09.14.28.png>)

Gallery grid on tablet:
![Full page on tablet](<static/images/Captura de ecrã 2025-06-17, às 09.15.29.png>)

Gallery grid on mobile:
![Full page on mobile](<static/images/Captura de ecrã 2025-06-17, às 09.15.41.png>)

## Tecnologies Used

    •	HTML5 & CSS3
    •	Flexbox (for navigation alignment)
    •	CSS Grid (for image gallery distribution and alignment)
    •	Media Queries for responsive design
