# Dashboard App

This project is a dashboard application built with React.js and Vite. It includes a sidebar, a top area with a date range picker, and other components to visualize data.

## Project Structure

dashboard-app/
├── node_modules/
├── public/
├── src/
│ ├── assets/
│ ├── components/
│ │ ├── dashboard/
│ │ │ ├── AreaTop.jsx
│ │ │ └── ... (other components)
│ │ ├── sidebar/
│ │ └── ... (other components)
│ ├── constants/
│ ├── context/
│ ├── layout/
│ ├── screens/
│ │ ├── dashboard/
│ │ ├── error/
│ │ └── ... (other screens)
│ ├── App.jsx
│ ├── App.scss
│ ├── index.js
│ └── index.html
├── .eslintrc.js
├── .gitignore
├── package.json
└── vite.config.js

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Make sure you have Node.js and npm installed on your system. If not, you can download and install them from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repo

   git clone https://github.com/prabinmagar/tabernam-admin-template-in-react-js.git


# Navigate to the project directory
    cd dashboard-app
    

# Install NPM packages
    npm install


### Running the Application

# Start the development server
    npm run dev


## Design Choices

React.js: Chosen for its component-based architecture, allowing for reusable UI components.
Vite: Selected for its fast development build times and efficient HMR (Hot Module Replacement).
React Icons: Used for including icons in the project due to its comprehensive library and ease of use.
react-date-range: Implemented for the date range picker functionality, providing a simple yet powerful date range selection component.
Context API: Used for managing global state, such as sidebar visibility, ensuring a cleaner and more maintainable state management solution.

# Challenges Faced

Date Range Picker Integration: Integrating the react-date-range package required handling CSS imports correctly and ensuring the component's state updates worked seamlessly.
Sidebar Toggle: Managing the state of the sidebar using Context API while maintaining performance and responsiveness was a bit challenging but was resolved by proper state management and context usage.
Vite Configuration: Adjusting Vite configurations to work smoothly with various npm packages and ensuring fast build times and HMR.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
