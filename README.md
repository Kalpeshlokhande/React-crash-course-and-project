# React Crash Course

This project is a React application built with Vite. It's a crash course project that demonstrates the fundamentals of React, including components, routing, and data fetching.

## Installation

To get started with this project, clone the repository and install the dependencies.

```bash
git clone <repository-url>
cd react-crash-course
npm install
```

## Usage

To start the development server, run the following command:

```bash
npm run dev
```

This will start the development server at `http://localhost:3000`.

To build the project for production, run the following command:

```bash
npm run build
```

This will create a `dist` directory with the production-ready files.

To run the JSON server, run the following command:

```bash
npm run server
```

This will start a JSON server at `http://localhost:8000` that serves the data from `src/jobs.json`.

## Dependencies

### Production Dependencies

- react: ^19.1.1
- react-dom: ^19.1.1
- react-icons: ^5.5.0
- react-router-dom: ^7.9.1
- react-spinners: ^0.17.0
- react-toastify: ^11.0.5

### Development Dependencies

- @eslint/js: ^9.33.0
- @types/react: ^19.1.10
- @types/react-dom: ^19.1.7
- @vitejs/plugin-react: ^5.0.0
- autoprefixer: ^10.4.21
- eslint: ^9.33.0
- eslint-plugin-react-hooks: ^5.2.0
- eslint-plugin-react-refresh: ^0.4.20
- globals: ^16.3.0
- json-server: ^1.0.0-beta.3
- postcss: ^8.5.6
- tailwindcss: ^3.4.17
- vite: ^7.1.2

## Components

The following components are used in this project:

- `Card`
- `Hero`
- `HomeCards`
- `JobListing`
- `JobListings`
- `Navbar`
- `Spinner`
- `ViewAllJobs`

## Project Structure

```
react-crash-course/
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
├── README.md
├── tailwind.config.js
├── vite.config.js
├── node_modules/
├── public/
│   └── vite.svg
└── src/
    ├── App.jsx
    ├── index.css
    ├── jobs.json
    ├── main.jsx
    ├── assets/
    │   └── images/
    │       └── logo.png
    ├── components/
    │   ├── Card.jsx
    │   ├── Hero.jsx
    │   ├── HomeCards.jsx
    │   ├── JobListing.jsx
    │   ├── JobListings.jsx
    │   ├── Navbar.jsx
    │   ├── Spinner.jsx
    │   └── ViewAllJobs.jsx
    ├── layouts/
    │   └── MainLayout.jsx
    └── pages/
        ├── AddJobPage.jsx
        ├── EditJobPage.jsx
        ├── HomePage.jsx
        ├── JobPage.jsx
        ├── JobsPage.jsx
        └── NotFoundPage.jsx
```