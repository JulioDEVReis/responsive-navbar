# Responsive Navigation Menu

This project showcases a responsive website featuring a modern navigation system with effects.

## Project Structure

```
.
├── README.md
├── static
│   ├── css
│   ├── images
│   └── js
├── templates
│   └── index.html
└── tree.txt
```

## Desktop Navigation Design

The desktop navigation features a header with a semi-transparent background and backdrop blur effect. The header remains fixed at the top of the viewport, providing consistent access to navigation elements throughout the user’s browsing experience.
The navigation bar utilizes flexbox layout to achieve optimal spacing between the logo and navigation elements. The “Clínica Vida” logo is positioned on the left side with hover effects that transition to a lighter blue (#4a90e2), while the main navigation links (Home, Services, Doctors, Contact) and the language switcher (PT/EN) positioned on the right side. Each navigation element features smooth hover transitions that enhance user interaction feedback.

## Mobile Navigation Implementation

The mobile navigation system transforms the horizontal layout into a collapsible hamburger menu for screens below 768px. This responsive transformation ensures optimal usability across all device types. The hamburger icon consists of three horizontal bars that animate smoothly when activated, providing clear visual feedback to users.
When the hamburger menu is activated through the checkbox input mechanism, the navigation menu slides down from the top with a translateY transformation. The mobile menu features a semi-transparent background with backdrop blur effects. Navigation links stack vertically with increased padding for touch-friendly interaction.
