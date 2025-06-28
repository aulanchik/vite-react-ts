# Vite + React + TypeScript Project Template

A clean and modern starter template for building web applications with Vite, React, and TypeScript. This repository is configured with essential tools to ensure a fast and efficient development workflow.

## Features

-   **Frameworks**: React 19 and TypeScript 5.8
-   **Build Tool**: Vite 7 for blazing-fast development server and builds.
-   **Linting**: ESLint configured with recommended rules for TypeScript and React.
-   **Code Formatting**: Prettier setup for consistent code style.
-   **Path Aliases**: Pre-configured `@` alias for `src/` directory for cleaner import paths.
-   **Dependency Management**: Dependabot is configured to keep dependencies up-to-date automatically.

## Getting Started

To use this template, you can either click the "Use this template" button on the GitHub repository page or clone the repository manually.

### Installation

1.  Clone the repository to your local machine:
    ```bash
    git clone https://github.com/aulanchik/vite-react-ts.git your-project-name
    ```

2.  Navigate into your new project directory:
    ```bash
    cd your-project-name
    ```

3.  Install the dependencies using npm:
    ```bash
    npm install
    ```

## Available Scripts

This template includes the following scripts defined in `package.json`:

-   **`npm run dev`**
    Starts the development server with Hot Module Replacement (HMR).

-   **`npm run build`**
    Compiles TypeScript and bundles the application for production. The output is generated in the `dist/` directory.

-   **`npm run lint`**
    Lints the source code using ESLint to catch errors and enforce coding standards.

-   **`npm run preview`**
    Starts a local server to preview the production build from the `dist/` directory.
