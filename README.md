# Wanderlust Explorer

A travel experience discovery platform built with Next.js and React. Explore destinations, discover activities, search and filter experiences, and save favorites through a modern, responsive interface.

## Overview

Wanderlust Explorer is a multipage web application designed to make discovering travel experiences simple and intuitive.

The project focuses on frontend development, component-based architecture, dynamic navigation, URL-based search and filtering, and state management.

Users can browse a collection of travel experiences, explore individual details, and organize their favorite activities.

## Features

### Home
- Landing page with a hero section.
- Main call-to-action to access the experience explorer.

### Experience Explorer
- Browse a collection of travel experiences.
- Search experiences by title.
- Filter by category and destination.
- Combine search terms and filters.
- Synchronize search and filter values with URL query parameters.
- Restore active filters when opening a shared URL.

### Experience Details
- Dedicated page for each experience.
- Dynamic routing using the experience ID.
- Detailed information retrieved from the local dataset.

### Favorites
- Add or remove experiences from favorites.
- View saved experiences in a dedicated page.
- Manage favorites using React component state.

### User Profile
- Simulated user profile page.
- Display the current number of saved favorites.

## Experience Categories

The application dataset includes experiences across five categories:

- Adventure
- Culture
- Food
- Wellness
- Nature

The local dataset is designed to contain 100 travel experiences, including titles, descriptions, destinations, prices, ratings, and image references.

## Technology Stack

- **Next.js 16** — React framework and application routing.
- **React 19** — Component-based user interface.
- **TypeScript** — Static typing and maintainable code.
- **Tailwind CSS 4** — Utility-first styling.
- **ESLint** — Code quality and linting.

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/wendy-sanchez/aie-pt-3--nextjs-wanderlust-explorer.git
   ```

2. Navigate to the project directory:

   ```bash
   cd aie-pt-3--nextjs-wanderlust-explorer
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server. |
| `npm run build` | Build the application for production. |
| `npm run start` | Start the production server. |
| `npm run lint` | Run ESLint checks. |

## Design References

The visual direction was informed by research into travel and experience discovery platforms, including:

- Looking Travel
- Diario de un Mentiroso
- GetYourGuide

The design approach focuses on visual experience cards, high-quality imagery, intuitive search and filtering, clear content hierarchy, and responsive layouts.

## Project Documentation

- `SPEC.md` — MVP requirements, application routes, search and filtering behavior, dataset structure, and acceptance criteria.
- `docs/images/` — Design reference images.

## Project Goals and Learning Outcomes

This project explores practical frontend development concepts, including:

- Building multipage applications with Next.js.
- Creating reusable React components.
- Implementing dynamic routes.
- Managing application state with React.
- Synchronizing UI state with URL query parameters.
- Combining search and multiple filters.
- Structuring and consuming local TypeScript datasets.
- Designing responsive and user-friendly interfaces.

## Project Status

Developed as a frontend application project, with a focus on travel experience discovery and interactive user interfaces.

---

**Developer Wendy Sanchez**
