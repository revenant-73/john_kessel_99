# Repository Guidelines

## Project Structure & Module Organization
This repository is a single-page application designed as a coaching guide for new volleyball coaches. It is built using **HTML5**, **Tailwind CSS** (via CDN), and vanilla **JavaScript**.

- **index.html**: The core file containing all HTML, CSS (Tailwind configuration), and logic.
- **sourceinfo.txt**: Reference text containing the 19 principles and coaching details used to populate the application.
- **Content Management**: The "Principles" are defined as a JavaScript array (`principles`) within `index.html` and injected into the DOM dynamically.

## Build, Test, and Development Commands
There is no automated build system or package manager (e.g., npm, yarn). 

- **To View**: Open `index.html` directly in any modern web browser.
- **Live Preview**: Use a simple local server if needed (e.g., Python `http.server` or VS Code Live Server extension).

## Coding Style & Naming Conventions
- **Styling**: All styling is handled through Tailwind utility classes. Avoid writing custom CSS in `<style>` blocks unless absolutely necessary for complex transitions.
- **Scripting**: Use vanilla JavaScript for DOM manipulation and event handling.
- **Naming**: Use descriptive class names and IDs that reflect the component's purpose (e.g., `principles-grid`, `side-drawer`).

## Testing Guidelines
No formal test framework is integrated. Manual verification of the UI and interactive elements (like the side drawer) in the browser is required after making changes.

## Commit & Pull Request Guidelines
Follow simple and descriptive commit messages. The repository started with an `Initial-commit`. Example: `Update Principle 15 description` or `Add styling to the navigation bar`.
