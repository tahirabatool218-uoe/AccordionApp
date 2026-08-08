# Accordion App

A responsive React Accordion application that allows users to expand and collapse items using Single Selection and Multi Selection modes.

## Features

# Accordion App

## Project Title

Accordion App

## Short Description

A small, component-driven React application that displays expandable accordion items with support for single-item or multi-item selection modes.

## Features

- Expand and collapse accordion items
- Single selection mode (only one item open)
- Multiple selection mode (several items open)
- Toggle to switch between selection modes
- Reusable components (Accordion, AccordionItem)
- Responsive CSS styling

## Tech Stack

- React
- Vite
- JavaScript (ES6+)
- CSS

## How to Run

1. Install dependencies

```bash
npm install
```

2. Run the development server

```bash
npm run dev
```

3. Build for production

```bash
npm run build
```

Open the local URL shown by the dev server to view the app.

## Live Demo + GitHub Repository

- Live Demo:https://accordion-app-eight.vercel.app
- GitHub Repository: https://github.com/tahirabatool218-uoe/AccordionApp


## Project Structure

```text
accordion-app/
├── public/
├── src/
│   ├── components/
│   │   ├── Accordion.jsx
│   │   ├── AccordionItem.jsx
│   │   └── Accordion.css
│   ├── data/
│   │   └── accordionData.js
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
├── README.md
└── .gitignore
```

## Notes

The app uses React `useState` to manage the active accordion item(s) and the multiple-selection toggle. The `Accordion` component renders the `AccordionItem` component for each item in the `accordionData` array. 