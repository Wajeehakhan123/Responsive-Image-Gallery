# Responsive-Image-Gallery
Project Overview

This project is a fully responsive image gallery built using HTML, Tailwind CSS, and vanilla JavaScript. It displays a large collection of images in a grid layout with category filtering, a lightbox modal view, keyboard navigation, and a light/dark theme toggle.

The gallery is suitable for portfolios, blogs, photography websites, or any project that needs a modern, interactive image showcase.

Key Features
1. Responsive Grid Layout

Uses CSS Grid to display images

Automatically adjusts columns based on screen size:

Desktop: 4 columns

Tablet: 3–2 columns

Mobile: 1 column

Maintains a consistent 4:3 aspect ratio for all images

2. Dynamic Image Rendering

Images are stored in a JavaScript array (galleryItems)

Gallery items are generated dynamically using JavaScript

Each image includes:

Image source (URL)

Alternative text

Caption

Category (nature, food, people, architecture, etc.)

3. Category Filter System

Dropdown menu allows filtering images by category

Categories include:

Nature

Architecture

People

Animals

Food

Abstract

Urban

Travel

Selecting a category updates the gallery instantly

“All Categories” resets the view

4. Image Modal (Lightbox View)

Clicking an image opens it in a fullscreen modal

Modal displays:

Large image preview

Caption text

Close button

Previous & Next navigation buttons

Background scrolling is disabled while modal is open

5. Keyboard Navigation

Enhances accessibility and usability

Supported keys:

Esc → Close modal

← (Left Arrow) → Previous image

→ (Right Arrow) → Next image

6. Light & Dark Theme Toggle

Toggle switch allows users to switch themes

Changes:

Background colors

Text colors

Header and modal appearance

Implemented using JavaScript without external libraries

7. Performance Optimizations

Images use loading="lazy" to improve page load speed

Smooth hover and fade-in animations

Efficient DOM updates during filtering

Technologies Used

HTML5 – Structure and layout

Tailwind CSS – Utility-first styling and responsiveness

JavaScript (Vanilla) – Dynamic rendering, filtering, modal logic

Remix Icons – UI icons

Google Fonts – Typography (Inter & Pacifico)

Project Structure (Conceptual)

index.html – Main HTML structure

Embedded CSS – Custom styles and animations

Embedded JavaScript – Gallery data, modal logic, filters, theme toggle

Use Cases

Photography portfolio

Travel blog

Art or design showcase

Educational image collections

Magazine or media galleries

Customization Guide (Theory)

Add images: Insert new objects into the galleryItems array

Add categories: Create a new category name and assign it to images

Change layout: Modify grid columns in .gallery-grid

Replace images: Update image URLs with your own assets

Conclusion

This gallery demonstrates how a modern, interactive UI can be built using simple web technologies without heavy frameworks. It is scalable, user-friendly, and easy to customize for real-world projects.
