# Personal Portfolio Website

A comprehensive, responsive personal portfolio website designed to showcase professional qualifications, technical skills, and a diverse creative body of work. Built with modern web standards, it emphasizes clean aesthetics, user experience, and performance.

## Overview

This project serves as a digital curriculum vitae and creative gallery. It is structured into two main experiences:

1.  **Professional Profile (`index.html`)**: Focuses on the "Who" and "What".
    *   **About & Background**: interactive tabs displaying education and professional experience history.
    *   **Competency**: A detailed breakdown of technical, creative, and interpersonal skills with proficiency meters.
    *   **Services & Contact**: Professional offerings and direct communication channels.

2.  **Creative Gallery (`portfolio.html`)**: Focuses on the "Work".
    *   **Project Album**: Showcase of technical and IoT projects using a responsive card grid.
    *   **Video Album**: Curated collection of video productions (Music Videos, Documentaries, etc.), optimized with lightweight thumbnails.
    *   **Photo & Action Albums**: Extensive photography collections displayed in a "tidy," masonry-style collage layout that respects original aspect ratios.

## Key Features

*   **Responsive Design**: Fully fluid layouts that adapt seamlessly from mobile devices to large desktop screens.
*   **Performance Optimized**:
    *   Replaced heavy YouTube `<iframe>` embeds with lightweight thumbnails (`maxresdefault`/`hqdefault`).
    *   Migrated external image dependencies to local assets for faster loading and reliability.
*   **Modern Layouts**:
    *   **CSS Grid**: Used for structured content like Skills and Project Cards.
    *   **CSS Columns (Masonry)**: Utilized for the Photo and Action albums to create a dynamic, organic collage effect without rigid cropping.
*   **Dark/Light Theme**: Native support for theme switching (if implemented in current CSS/JS).

## Technology Stack

*   **HTML5**: Semantic markup for accessibility and SEO.
*   **CSS3**: Custom properties (Variables), Flexbox, Grid, and Multi-column layouts.
*   **JavaScript**: DOM manipulation for tabs, scroll interaction, and mobile navigation.

## How to Run

Since this is a static website, deployment and testing are straightforward.

### Local Development
You can view the site directly by opening `index.html` in any modern web browser.

**Recommended:** Use a local development server to ensure all routing and assets behave closer to a production environment.
*   **VS Code Live Server**: Right-click `index.html` -> "Open with Live Server".
*   **Python**: Run `python -m http.server` in the project directory and visit `http://localhost:8000`.
*   **PHP**: Run `php -S localhost:8000` and visit `http://localhost:8000`.

## File Structure

*   `index.html`: Main landing page (Profile, Skills, Experience).
*   `portfolio.html`: Gallery page (Projects, Videos, Photos).
*   `assets/`:
    *   `css/`: Stylesheets (Main layout, variables, responsive rules).
    *   `js/`: Interactive logic (Menu toggle, scroll active links).
    *   `img/`: Optimized local image assets.
