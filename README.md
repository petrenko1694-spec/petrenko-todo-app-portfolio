# Todo App

A browser-based todo list for organizing everyday tasks. The app is built with React and TypeScript and uses the Mate Academy students API to store todos.

**Live demo:** [petrenko1694-spec.github.io/petrenko-todo-app-portfolio](https://petrenko1694-spec.github.io/petrenko-todo-app-portfolio/)

## Features

- Create, edit, complete, and delete todos.
- Filter the list by all, active, or completed todos.
- Mark all todos complete or active and clear completed todos.
- See remaining-task counts and feedback when an API request fails.

## Technologies Used

### Core

- **React (`^18.3.1`)** — builds the interactive user interface.
- **TypeScript (`^5.2.2`)** — adds static typing to the application.
- **Sass/SCSS (`^1.77.8`)** — styles the app with SCSS.

### UI

- **Bulma (`^1.0.1`)** — provides base UI styles.
- **Font Awesome (`^6.5.2`)** — supplies icon fonts.
- **classnames (`^2.5.1`)** — applies CSS classes conditionally.

### Development and deployment

- **Vite (`^5.3.1`)** — runs the development server and builds the app.
- **ESLint (`^8.57.0`)** — checks code quality.

## Getting started

### Prerequisites

- Node.js 20
- npm

### Install and run

```bash
git clone https://github.com/petrenko1694-spec/petrenko-todo-app-portfolio.git
cd petrenko-todo-app-portfolio
npm install
npm start
```

The development server prints its local URL in the terminal.

### Use the app

Type a task into the input at the top of the page and press Enter to add it. Use the checkbox to mark it complete, double-click its title to edit it, or select the × button to delete it. The footer provides status filters and a **Clear completed** action.

The app sends requests to the Mate Academy students API. The user ID is configured as `USER_ID` in [`src/api/todos.ts`](src/api/todos.ts); set it to the ID assigned to you if you are running your own copy.

### Production build

```bash
npm run build
```

Vite writes the production build to `dist/`.

## Maintainers and contributions

Maintained by Oleksii Petrenko.
