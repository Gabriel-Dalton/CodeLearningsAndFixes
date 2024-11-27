# Code Learnings and Fixes

Welcome to **Code Learnings and Fixes**, a personal documentation repository where I share my experiences in coding. This includes challenges I've faced, solutions I've implemented, and the insights I've gained along the way. It's my coding journal to reflect on and track progress.

---

## Purpose

This repository serves as:
- A **learning journal** to document coding issues and their solutions.
- A resource to revisit previous problems and resolutions.
- An opportunity to help others who may encounter similar challenges.

---

## How It Works

1. **Structure**:
    - Each learning or issue is logged in a markdown file (`.md`) in the `entries` folder.
    - The files are named based on the topic or issue for easy reference.

2. **Entry Format**:
    Each log entry includes:
    - **Title**: A concise summary of the problem or topic.
    - **Date**: The date the issue was encountered or resolved.
    - **Description**: A brief explanation of the problem or concept.
    - **Solution**: Steps or code snippets showing how the issue was resolved.
    - **Lessons Learned**: Insights gained from solving the problem.

---

## Example Entry

### Title: "Fixing Dropdown Menu in Mobile Nav"
- **Date**: November 26, 2024
- **Description**:
  I encountered an issue where the dropdown menu in the mobile navbar wasn't toggling when moved to an external JS file.
- **Solution**:
  - Used `DOMContentLoaded` to ensure the DOM was fully loaded before running the script.
  - Added `defer` to the `<script>` tag in the HTML.
- **Lessons Learned**:
  - Ensure scripts are executed only after DOM elements are available.
  - Debug using browser dev tools to check for errors or missing files.

