# React State Filter App

This repository contains a project completed for a university **Software Engineering** course. The goal of the project was to practice building web applications using **ReactJS** while following common project structure and development workflows.

The project demonstrates building reusable React components, handling user input, and switching between different views of an application.

---

## Project Overview

The application includes several React components and pages that demonstrate how a small web application can be structured.

Key features include:

* A component that displays user information and a motto
* A searchable list of U.S. states
* A reusable header component
* The ability to switch between different views
* URL-based navigation using React Router

---

## Example Component

The Example component displays a user's name and motto.

This part of the project demonstrates:

* Using React components
* Basic styling with CSS

---

## States Component

The States component allows the user to search for U.S. states using a text input.

As the user types, the list of states updates automatically to show only states containing the entered substring.

Example:

Input:

```
al
```

Result:

```
Alabama
Alaska
California
```

Features of this component:

* Real-time filtering as the user types
* Case-insensitive search
* Displays a message when no states match
* Displays all states when the input is empty

---

## Header Component

A reusable Header component was created to provide a consistent layout across the different pages of the application.

The header includes custom styling and is used in multiple views throughout the project.

---

## Switching Between Views

The project includes multiple pages that demonstrate different React components.

One version allows switching between views using a button.

A later version uses **React Router** to enable navigation between views using the URL. This allows users to refresh the page or bookmark a specific view.

Example URLs:

```
#/example
#/states
```

---

## Development Tools

This project uses several tools commonly used in modern JavaScript development:

* **Webpack** for bundling JavaScript files
* **Babel** for compiling JSX
* **ESLint** for checking code quality
* **Node.js** and **Express** for running a local development server

---

## Running the Project

1. Install dependencies

```
npm install
```

2. Build the project

```
npm run build
```

3. Start the development server

```
node webServer.js
```

The application will be available at:

```
http://localhost:3000
```

---

## Purpose

The goal of this project was to gain hands-on experience with ReactJS, component-based design, and modern JavaScript development tools.
