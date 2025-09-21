# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

React Context API Learning Project

This project is a simple React application designed to demonstrate the use of React Context API for state management across components without prop drilling.

Features

Global theme toggle (Light / Dark mode)

User authentication state simulation

Counter example shared across multiple components

Avoids prop drilling


Installation
# Clone the repository
git clone https://github.com/yourusername/context-api-learning.git

# Navigate to project directory
cd context-api-learning

# Install dependencies
npm install
# or
yarn install

# Start the development server
npm start
# or
yarn start


Open http://localhost:3000
 to view it in your browser.

Folder Structure
src/
├─ components/        # Reusable components
│  ├─ Header.jsx
│  └─ Counter.jsx
├─ context/           # Context API files
│  └─ ThemeContext.jsx
├─ App.jsx
└─ main.jsx
