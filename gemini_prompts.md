# Project Development Prompts for Gemini

This collection outlines the key prompts used throughout the lifecycle of developing this project, categorized by phase.

---

## 1. Project Planning & Architecture

### High-Level Planning
> "Acts as a Senior Software Architect. Help me plan a single-file web application for [insert project topic/idea]. Provide a recommended tech stack (HTML/Tailwind CSS/JavaScript or React) and outline the core features needed for a Minimal Viable Product (MVP)."

### Tech Stack Selection
> "What are the pros and cons of using React with Tailwind CSS versus plain HTML/JS for building a lightweight single-file web application?"

---

## 2. UI/UX Design & Layout

### Initial UI Wireframe
> "Design a clean, modern, and responsive user interface layout for [project name] using Tailwind CSS. Include a header, navigation bar, interactive dashboard area, and footer."

### Styling & Theme Customization
> "Suggest a cohesive color palette (dark mode and light mode) using Tailwind CSS classes suitable for a modern web dashboard."

---

## 3. Frontend Development & Logic

### Component Design
> "Write a React component for a stateful [feature name, e.g., Filterable Data Table / Interactive Form]. Ensure state is managed cleanly using React hooks."

### Single-File Application Generation
> "Create a complete, fully functional single-file web application using HTML, Tailwind CSS (via CDN), and vanilla JavaScript for [project core feature]. Ensure all logic and styles are included in one file."

---

## 4. State Management & API Integration

### Mock Data & State Logic
> "Generate sample JSON data representing [data entity, e.g., user profiles / tasks / metrics] and provide JavaScript functions to create, read, update, and delete items from this state array."

### API Integration
> "Write an asynchronous JavaScript function using `fetch` to retrieve data from a REST API and handle loading states, success responses, and error handling gracefully."

---

## 5. Refactoring, Optimization & Quality Assurance

### Code Clean-up
> "Review the following JavaScript code for readability, maintainability, and efficiency. Suggest refactoring steps to improve code structure without changing functional behavior."

### Responsive & Accessibility Fixes
> "How can I improve the ARIA accessibility attributes and mobile responsiveness for this navigation menu component?"

---

## 6. Documentation & Maintenance

### README Generation
> "Write a comprehensive `README.md` file for this project. Include an overview, feature list, setup instructions, technology stack, and potential future improvements."

### Inline Code Documentation
> "Add clear JSDoc inline documentation and comments to the following JavaScript functions explaining parameters, return types, and business logic."