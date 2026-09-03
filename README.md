# React Todo Basics

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A lightweight, zero-build Todo List application built to learn the core fundamentals of React: state management, event handling, and dynamic rendering.

## Overview

This project explores the three essential pillars of React without the overhead of a complex build toolchain. By relying purely on an HTML file with React and Babel loaded via CDN, it strips away configuration complexity to focus strictly on component logic.

### Core Concepts

State: Managing and updating the live array of tasks.

Events: Capturing user inputs to add, complete, and delete items.

Rendering: Dynamically mapping state arrays to live UI elements.

## How it works

This single-page application functions as an interactive task manager that lets users add, check off, and delete daily to-do items directly in the browser interface.

Unlike typical React applications that require Node.js, npm, and a bundler (such as Vite or Webpack), this project loads React, ReactDOM, and Babel directly via CDN script tags inside a single HTML file. Babel compiles the JSX in real time within the browser, allowing for instant execution without a local build step.

## Project Structure

```
react-todo-basics/
│
├── index.html       # Single-file implementation (HTML, CSS, and React logic)
└── README.md
```

## License

MIT