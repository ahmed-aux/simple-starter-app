# React + Vite WebContainer App 🚀

A modern React application built with Vite, TypeScript, and featuring Hot Module Replacement (HMR).

## Features

- ⚛️ React 18.2
- ⚡ Vite 5.1 for lightning-fast development
- 📘 TypeScript support
- 🔥 Hot Module Replacement (HMR)
- 🎨 Interactive demos:
  - Counter component
  - Todo list with CRUD operations

## Project Structure

```
react-webcontainer-project/
├── index.html          # Entry HTML file
├── package.json        # Project dependencies
├── tsconfig.json       # TypeScript configuration
├── vite.config.js      # Vite configuration
└── src/
    ├── main.tsx        # Application entry point
    ├── App.tsx         # Main App component with demos
    └── index.css       # Global styles
```

## Getting Started

### Install Dependencies

```bash
npm install
```

### Run Development Server

```bash
npm start
```

The application will start on http://localhost:3111

## What's Included

### Counter Demo

A simple counter with increment and reset functionality to demonstrate state management.

### Todo List Demo

A fully functional todo list with:

- Add new todos
- Delete todos
- Keyboard support (press Enter to add)

## Technologies

- **React**: UI library
- **Vite**: Build tool and dev server
- **TypeScript**: Type-safe JavaScript
- **@vitejs/plugin-react**: React plugin for Vite with Fast Refresh

## Development

Edit `src/App.tsx` to see changes instantly with HMR. The dev server is configured to run on port 3111 with polling enabled for better compatibility.

## License

Private project
