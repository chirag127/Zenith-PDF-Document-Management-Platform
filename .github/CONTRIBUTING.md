# CONTRIBUTING GUIDELINES FOR ZenithPDF-Client-Side-Document-Management-Desktop-App

Welcome to the ZenithPDF project! We appreciate your interest in contributing to this high-performance, privacy-first desktop application.

## 1. CODE OF CONDUCT

This project adheres to the Contributor Covenant Code of Conduct. Please review the [CODE_OF_CONDUCT.md](https://github.com/chirag127/ZenithPDF-Client-Side-Document-Management-Desktop-App/blob/main/CODE_OF_CONDUCT.md) file for details on expected behavior.

## 2. GETTING STARTED

### 2.1. Prerequisites

Ensure you have the following installed:

*   **Node.js:** Latest LTS version.
*   **npm or Yarn:** Package manager.
*   **Rust:** Latest stable version (required by Tauri).
*   **Tauri CLI:** Install via `cargo install tauri-cli`.
*   **Git:** For version control.

### 2.2. Setting Up the Development Environment

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/ZenithPDF-Client-Side-Document-Management-Desktop-App.git
    cd ZenithPDF-Client-Side-Document-Management-Desktop-App
    

2.  **Install Dependencies:**
    bash
    # Using npm
    npm install

    # Or using Yarn
    yarn install
    

3.  **Run the Development Server:**
    bash
    # Using npm
    npm run tauri dev

    # Or using Yarn
    yarn tauri dev
    

This will start the application in development mode, allowing you to see changes in real-time.

## 3. CONTRIBUTION WORKFLOW

We follow a standard GitHub pull request workflow:

1.  **Fork the Repository:** Create your own fork of the `chirag127/ZenithPDF-Client-Side-Document-Management-Desktop-App` repository.
2.  **Create a New Branch:** Branch out from `main` for your feature or bug fix. Use a descriptive name (e.g., `feature/add-new-conversion-format`, `fix/memory-leak-in-editor`).
    bash
    git checkout -b your-branch-name
    
3.  **Make Your Changes:** Implement your changes, ensuring they adhere to the project's coding standards and architectural principles.
4.  **Test Your Changes:** Run the automated tests to ensure your changes haven't introduced regressions. Add new tests if applicable.
    bash
    # Run linters and formatters
    npm run lint
    npm run format

    # Run unit tests
    npm run test:unit

    # Run E2E tests (if applicable)
    npm run test:e2e
    
5.  **Commit Your Changes:** Write clear, concise commit messages.
    bash
    git add .
    git commit -m "feat: Add XYZ functionality" # Or "fix: Resolve ABC bug"
    
6.  **Push to Your Fork:** Push your branch to your fork on GitHub.
    bash
    git push origin your-branch-name
    
7.  **Open a Pull Request:** Create a pull request from your fork's branch to the `main` branch of the `chirag127/ZenithPDF-Client-Side-Document-Management-Desktop-App` repository.
8.  **Address Feedback:** Respond to review comments and make necessary adjustments.

## 4. CODING STANDARDS & ARCHITECTURE

*   **Language:** TypeScript (Strict mode is enforced).
*   **Framework:** Tauri v2, Vite 7.
*   **Styling:** Tailwind CSS v4.
*   **Linting/Formatting:** Biome (configured for speed and consistency).
*   **Testing:** Vitest (Unit Tests), Playwright (End-to-End Tests).
*   **Architecture:** Adhere to Feature-Sliced Design (FSD) principles for maintainable code organization.
*   **Principles:** Follow SOLID, DRY, and YAGNI principles.
*   **Type Safety:** Strive for maximum type safety. Avoid `any` unless absolutely necessary and documented.

## 5. SUBMITTING A BUG REPORT

If you encounter a bug, please submit an issue using the provided bug report template. Provide as much detail as possible, including:

*   Steps to reproduce the bug.
*   Expected behavior vs. actual behavior.
*   Environment details (OS, Tauri version, etc.).
*   Screenshots or screen recordings if helpful.

## 6. SUGGESTING AN ENHANCEMENT

For feature requests, please open an issue and use the enhancement template. Clearly articulate the proposed feature and its benefits.

## 7. PULL REQUEST TEMPLATE

Ensure your pull request adheres to the structure defined in the [PULL_REQUEST_TEMPLATE.md](https://github.com/chirag127/ZenithPDF-Client-Side-Document-Management-Desktop-App/blob/main/PULL_REQUEST_TEMPLATE.md).

## 8. SECURITY

If you discover a security vulnerability, please follow the guidelines in the [SECURITY.md](https://github.com/chirag127/ZenithPDF-Client-Side-Document-Management-Desktop-App/blob/main/SECURITY.md) file.

Thank you for contributing!
