# Project Name: App(O)

(Alternative names: O-Meter, BigO Inspector)

### Document Version

Author: King Sambonge
Date: April 18, 2025
Version: 1.0


## Executive Summary

I am creating a web application that allows users to input code snippets and instantly receive an analysis of their time and space complexity.

This project aims to bridge the gap in understanding Big O notation among developers. 

It is valuable because it empowers developers to write more efficient and scalable code, solving a key technical weakness across many experience levels: many developers struggle to estimate or understand how their code performs at scale. It's also a tool that can grow into algorithm comparison, scaling predictions, and optimization recommendations in the future.


## Goals and Objectives

**Primary Goals (SMART):**

 * **Specific:** Build a working web app that analyzes and outputs Big O complexity for code snippets.

 * **Measurable:** Support at least Python, JavaScript, and Java for initial MVP.

 * **Achievable:** Focus on a simple MVP (minimum viable product) first: input field + output analysis + clean UI.

 * **Relevant:** Directly ties into my software development learning and passion.

 * **Time-bound:** Launch MVP within 2 months.

**Key Outcomes:**

 * Web app live and functional.

 * Ability to analyze basic algorithms (loops, recursion, nesting).

 * Clean and simple user interface.


## Scope Statement

**Included:**

 * Web app input field and output panel.

 * Support for Python, JavaScript, and Java in v1.

 * Time and space complexity analysis.

 * Simple frontend UI.

**Excluded:**

 * Compiler-level deep optimizations.

 * Machine Learning-based code analysis.

 * Mobile version.

 * User login/registration system (unless added later for saving snippets).


## Deliverables

 * Live hosted MVP Web Application.

 * Input form for code snippets.

 * Output showing Time Complexity, Space Complexity, and Explanation.

 * Basic documentation.


## Stakeholders

|    **Role**      |           **People**            |        **Interests/Responsibilities**           |
|------------------|---------------------------------|-------------------------------------------------|
| Project Lead     | *King Sambonge*                 |       Planning, coding, deployment.             |
| Users            | Developers, Students, Educators.| Quick and helpful Algorithm complexity analysis.|
| Mentors          | Educators, peers.               |         Feedback, testing advice.               |


## Timeline and Schedule

| **Phase**          | **Duration** |                **Tasks**                  |
|--------------------|--------------|-------------------------------------------|
| Planning           | 1 week	    |    Define MVP, Tech Stack selection.      |
| Design             | 1 week       |       Wireframe UI and UX flow.           |
| Development (MVP). | 4 weeks      | Build backend parser, frontend interface. | 
| Testing            | 1 week       |      Debugging, User Testing.             |
| Launch             | 1 week       | Deploy WebApp, share for early feedback.  |


## Resource Plan

 * **Time**: 5-8 hours weekly

 * **Budget**: ~$20/month (domain + hosting)

 * **Skills**: Web Development, Basic Code Parsing, Algorithm Complexity Knowledge


## Risk Management Plan

| **Risk**                      |         **Mitigation Strategy**             |
|-------------------------------|---------------------------------------------|
| Incorrect complexity analysis | Start simple: loops, recursion first.       |
| Time shortage                 | Strict MVP focus                            |
| Deployment issues             | Use well-supported free hosting services.   |
| Low user adoption             | Promote in coding communities               |


## Communication Plan

 * **Self-Tracking:** Weekly GitHub Projects board checklist

 * **Version Control:** GitHub repository with branches and commits

 * **Backup:** Regular GitHub commits and branches


## Success Metrics

 * Live MVP web app and operational

 * Supports at least three languages

 * Correctly analyzes basic algorithms

 * Minimum of 10 users within 1 month

 * 70% accuracy feedback rating from initial users


## Rough Tech Stack

* **Frontend:**

	* HTML5

	* CSS3 (optionally Tailwind CSS)

	* JavaScript

* **Backend:**

	* Python (Flask framework)

* **Parsing/Analysis:**

	* Custom parsing logic (initial MVP)

* **Hosting/Deployment:**

	* GitHub (repo)

	* Render, Vercel, or Railway for live deployment

* **Tools:**

	* Git for version control

	* GitHub Projects for task tracking





### Next Steps

 * Finalize tech stack decision.

 * Begin Planning Phase immediately.

 * Set up GitHub repo and basic file structure.


 **Future Growth:**

 * Compare the efficiency of different algorithms.

 * Predict how an algorithm's performance will scale with larger inputs.

 * Help users choose the most efficient algorithm for a given problem.

 * Build an extension version for VS Code allowing users to get complexity analysis directly inside their editor.

