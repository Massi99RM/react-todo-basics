# React Todo Basics

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A lightweight, multi-page zero-build React learning suite designed to explore foundational and intermediate React concepts through interactive implementations and a modular sandbox playground.

## Overview

This project expands beyond a simple task manager into a comprehensive learning hub. By maintaining a zero-build toolchain using CDNs and Babel standalone, it strips away configuration complexity, allowing developers to inspect real-time JSX compilation, shared stylesheets, and multi-page routing via vanilla JavaScript.

### Core Concepts

State Management: Tracking primitive, array, and boolean states using useState across multiple isolated components.

Event & Data Flow: Handling user interactions via onChange and onClick handlers, supporting dynamic task filtering (All, Active, Completed).

Side Effects & Asynchronous Logic: Utilizing useEffect to safely perform API data fetching, manage loading states, and handle network errors without triggering infinite render loops.

Component Architecture: Building reusable custom components with unique identifiers (id: Date.now()) and scalable prop structures.

## How it works

The project is structured into three distinct pages connected by a dynamic navigation bar that automatically detects the active route:

Todo App (index.html): Task manager with addition, completion toggling, deletion, and real-time category filtering

Concepts Guide (concepts.html): A reference documentation page breaking down core React pillars (State, Events, Rendering) with isolated code snippets from the codebase.

Interactive Playground (playground.html): Sandbox where visitors can dynamically mount and unmount custom React widgets, including a Counter, Live List, Toggle/Dark Mode Switch, and a Fetch Widget integrating live REST API requests..

## Project Structure

```
react-todo-basics/
│
├── index.html       # Interactive Todo list application
├── concepts.html    # React core concepts reference guide
├── playground.html    # Interactive widget builder sandbox
├── style.css        # Shared global stylesheet
├── .gitignore
└── README.md
```

## License

MIT