# React Agency Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Code of Conduct](https://img.shields.io/badge/Code%20of%20Conduct-v1.4-blue.svg)](CODE_OF_CONDUCT.md)

A modern, responsive Single Page Application (SPA) built with React.js, based on the classic "Agency" theme. This project demonstrates a clean, component-based UI architecture, dynamic routing, and professional form validation.

## Key Features

- **Responsive Design**: Built with a mobile-first approach using Bootstrap for full compatibility across devices.
- **Dynamic Routing**: Implements React Router DOM for seamless, zero-refresh client-side navigation.
- **Professional Form Validation**: Features a robust contact form integrated with Formik and Yup for sophisticated client-side validation.
- **Modular Component Architecture**: Organized into reusable components for Pages (Home, About, Services) and Common UI elements (Header, Footer, Portfolio Items).
- **Modern Interactive UI**: Includes smooth-scrolling sections, interactive portfolio modals, and polished hover effects.

## Tech Stack

- **Frontend Library**: [React.js](https://react.org/) (v19)
- **Routing**: [React Router DOM](https://reactrouter.com/) (v7)
- **Form Handling**: [Formik](https://formik.org/)
- **Validation**: [Yup](https://github.com/jquense/yup)
- **Styling**: Bootstrap 5, Custom CSS
- **Transpilation**: Babel (with modern ECMAScript standard support)

## Recent Improvements

To maintain high code quality and modern development standards, the following enhancements were recently implemented:

- **Environment Modernization**: Updated the Browserslist database to ensure optimal browser compatibility data.
- **Code Quality Cleanup**:
  - Performed a comprehensive ESLint audit and resolved build-time warnings.
  - Removed unused variables and redundant imports in `Field.js`, `Footer.js`, `PortfolioItem.js`, `About.js`, and `Home.js`.
  - Refined JSX syntax to align with React 19 standards and accessibility best practices.

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository**

   ```bash
   git clone https://github.com/aadhar41/React-Agency-Portfolio.git
   cd React-Agency-Portfolio
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Development Server**

   ```bash
   npm start
   ```

   The app will run in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Screenshots

| Home Page | Services Page | Portfolio Page |
| :---: | :---: | :---: |
| ![Home Page](public/pages/home-page.png) | ![Services Page](public/pages/services-page.png) | ![Portfolio Page](public/pages/portfolio-page.png) |
| **About Page** | **Team Page** | **Contact Us Page** |
| ![About Page](public/pages/about-page.png) | ![Team Page](public/pages/team-page.png) | ![Contact Us Page](public/pages/contactus-page.png) |

## Available Scripts

- `npm start`: Runs the app in the development mode.
- `npm test`: Launches the test runner.
- `npm run build`: Builds the app for production to the `build` folder.

## Community & Contribution

We welcome contributions! Please see our guides below to get started:

- [Contributing Guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Report a Bug](https://github.com/aadhar41/React-Agency-Portfolio/issues/new?template=bug_report.yml)
- [Request a Feature](https://github.com/aadhar41/React-Agency-Portfolio/issues/new?template=feature_request.yml)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Specialized for educational and portfolio purposes.
