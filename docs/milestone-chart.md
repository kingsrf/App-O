# Milestone Chart

## Key Milestones

Target Date    |                Milestone       |                                Description                                 | Status

April 7, 2025  | Project Kickoff & Requirements.|               Finalize scope, user stories, and technical stack            | Done

April 21, 2025 |         UI/UX Prototype        |             Complete wireframes and interactive React mockups              | Done

May 5, 2025    |    Core Analysis Engine        |       Implement AST parsing, traversal, and complexity rule engine         | Done

June 2, 2025   |       Visualization Module     | Build charts to plot theoretical and empirical performance in the React UI | In Progress

June 10, 2025  |            Testing & QA        | Run unit/integration tests, fix critical bugs, and validate end-to-end workflows | In Progress

June 16, 2025  |   Documentation & Tutorials    |      Write user guide, API reference, and record tutorial videos           | In Progress

June 22, 2025  |    MVP Deployment (React)      |           Deploy the React application to the demo site                    | Planned


## High-Level Timeline

Apr 2025          May 2025            Jun 2025
|
|  ● Project Kickoff (Apr 7)
|       |-● UI/UX Prototype (Apr 21)
|              |-● Core Engine (May 5)
|                            |-● Visualization (Jun 2)
|                                  |-● Testing & QA (Jun 10)
|                                        |-● Docs & Tutorials (Jun 16)
|                                               |-● React Deployment (Jun 22)

Plugin Integration - For later dev. V3


## Planned React Deployment Folder Structure

App-O/
|-- public/
|   |-- index.html
|   |-- assets/
|       |-- logo.png
|-- src/
|   |-- components/
|   |   |-- Chart.jsx
|   |   |-- Editor.jsx
|   |   |-- Layout.jsx
|   |--- engine/
|   |   |-- parser.js
|   │   |-- rules.js
|   |   |-- analyzer.js
|   |-- hooks/
|   |   |-- usePerformanceData.js
|   |-- styles/
|   |--   |-- globals.css
|   |-- App.jsx
|   |-- index.jsx
|   |-- reportWebVitals.js
|-- docs/
|   |-- milestone-chart.md
|-- .gitignore
|-- package.json
|-- README.md



## Core Analysis Engine Summary

- I designed the core analysis engine to transform user-submitted code into actionable complexity insights. I:

* Parsed source snippets into an AST using Babel or Acorn.

* Traversed the AST to identify loops, recursion, and nested structures.

* Encapsulated complexity patterns (e.g., O(n), O(n²), O(n log n)) in a rule engine.

* Formatted the results into a { time: 'O(n²)', space: 'O(n)' } object for seamless UI integration.


## Future Version Updates (v3+)

- I plan to enhance the tool in future releases by integrating a code-editor plugin that will:

* Support VS Code extensions and embedding in web editors.

* Offer commands in the editor’s command palette for on-demand analysis.

* Package and publish the extension to the VS Code Marketplace for easy adoption.