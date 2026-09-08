# Phone Catalog

## Introduction

Welcome to the Phone Catalog project, a React-based implementation of a modern e-commerce SPA (Single Page Application). This project provides an interactive gadget store experience where users can browse products, manage a shopping cart, and save favorite items. The application is developed using modern web technologies, emphasizing clean architecture and a seamless user experience.

## Key Features

* **Dynamic Routing:** Browse products across Phones, Tablets, and Accessories categories without page reloads.
* **URL Synchronization:** Sort items and choose display quantities, with all parameters fully synchronized with the URL for shareable links.
* **Shopping Cart:** Add items, adjust quantities, and calculate totals with data persisting across sessions.
* **Favorites System:** Bookmark favorite products, synced instantly with the header counter.
* **Responsive Design:** Ensures the store is fully functional and visually appealing on desktops, tablets, and mobiles.
* **UI/UX Enhancements:** Includes a custom Dark/Light theme switcher and loading skeletons for a smooth browsing experience.

## Challenges

Developing the Phone Catalog posed several challenges, particularly around state management and ensuring a smooth, bug-free user experience across different simulated API states.

**Key Challenges:**

* **URL State Synchronization:** Ensuring that sorting and pagination parameters accurately reflected the URL state on page reloads required precise handling of React Router hooks.
* **State Management:** Managing the shopping cart and favorites states across deeply nested components and keeping them perfectly synced with `localStorage` needed efficient React Context implementation.
* **Data Fetching Simulation:** Handling asynchronous data fetching from local JSON files while managing loading states (skeletons) and potential error states.
* **Swiper Integration:** Customizing the Swiper.js carousel to work flawlessly with React and custom CSS modules without breaking the mobile layout.

## Technical Requirements

To run this project, you will need:
* Modern web browser (latest versions of Chrome, Firefox, Safari, or Edge)
* Node.js (version 16.x or newer)
* NPM (version 8.x or newer)

## Installation and Setup

To install the project and run it locally, follow these steps:

Clone the repository:
```bash
git clone https://github.com//.git
```

Navigate to the project directory:
```bash
cd
```

Install dependencies:
```bash
npm install
```

Start the local development server:
```bash
npm start
```

## Usage

After starting the project, it will be available at http://localhost:3000. You can use this project to browse the catalog, add items to the cart, switch themes, and interact with all e-commerce interface elements.

## Example

* **Live Demo:** 🔗 [DEMO LINK](https://Kit3AWP.github.io/Phone_catalog/)
* **Design Specifications:** 🔗 [Figma Design 1](https://www.figma.com/file/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog-(V2)-Original) | 🔗 [Figma Design 2](https://www.figma.com/design/WMdJ24eHk4EkSr25mrt7Y2/Phone-catalog--V2--Original-Dark)

## Technologies Used

This project was built using the following technologies:
* **React (Hooks, Custom Hooks):** For building the component-based user interface.
* **TypeScript:** For static typing and reducing runtime errors.
* **React Context:** For global state management.
* **React Router v6:** For dynamic routing and URL parameter extraction.
* **SCSS Modules:** For scoped, maintainable, and desktop-first styling.
* **Swiper.js:** For touch-friendly carousels.

## Design Specifications

**Design Sizes:**
* Desktop: 1200px
* Tablet: 640px
* Mobile: > 320px
