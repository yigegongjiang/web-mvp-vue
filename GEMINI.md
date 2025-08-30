# GEMINI Code Companion

This document provides context for the Gemini AI code companion to understand the project structure, conventions, and commands.

## Project Overview

This is a Vue.js 3 project bootstrapped with Vite. It uses TypeScript for type safety and Pinia for state management. The project is set up with Vitest for unit testing.

- **Framework:** Vue.js 3
- **Build Tool:** Vite
- **Language:** TypeScript
- **State Management:** Pinia
- **Testing:** Vitest

## Building and Running

The following commands are available to build, run, and test the project:

- **Install dependencies:**
  ```sh
  bun install
  ```

- **Compile and Hot-Reload for Development:**
  ```sh
  bun dev
  ```

- **Type-Check, Compile and Minify for Production:**
  ```sh
  bun run build
  ```

- **Run Unit Tests:**
  ```sh
  bun test:unit
  ```

## Development Conventions

- **IDE:** VSCode with the Volar extension is recommended.
- **Type-Checking:** `vue-tsc` is used for type-checking `.vue` files.
- **Testing:** Unit tests are written with Vitest and are located in the `src/components/__tests__` directory.
- **Code Style:** The project follows the standard Vue.js style guide.
- **File Structure:**
    - `src/assets`: Static assets like CSS and images.
    - `src/components`: Reusable Vue components.
    - `src/router`: Vue Router configuration.
    - `src/stores`: Pinia store modules.
    - `src/views`: Vue components that represent pages.
