# Contributing to the Project

Thank you for your interest in contributing to our project! This document outlines the process for setting up the project locally, submitting issues, and creating pull requests to ensure a smooth collaboration.

## Table of Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setting Up the Project Locally](#setting-up-the-project-locally)
- [Submitting Issues](#submitting-issues)
- [Creating Pull Requests](#creating-pull-requests)

---

## Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:
- Node.js (LTS version recommended)
- Gulp CLI (`npm install --global gulp-cli`)
- Git

### Setting Up the Project Locally

1. Fork the repository:
   - Navigate to the [main repository](https://github.com/bsidesgrunn/bsidesgrunn.org.git).
   - Click the "Fork" button in the top-right corner to create a copy of the repository under your account.

2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/[bsidesgrunn.org].git
   ```

3. Navigate to the project directory:
   ```bash
   cd bsidesgrunn.org
   ```

4. Install dependencies:
   ```bash
   npm install
   ```

5. Set up environment variables:
   - Copy the example file: `cp .env.example .env`
   - Edit the `.env` file with your local settings (if applicable).

6. Start the development server:
   ```bash
   gulp
   ```

7. Open the project in your browser or development environment.

---

## Submitting Issues

If you find a bug, have a feature request, or have any other feedback, please submit an issue:

1. Navigate to the [Issues tab](link-to-issues).
2. Click "New Issue."
3. Choose the appropriate issue template.
4. Fill in the details and submit.

Be sure to include:
- A clear and descriptive title.
- Steps to reproduce the issue (if applicable).
- Expected and actual behavior.
- Screenshots or logs (if helpful).

---

## Creating Pull Requests

Follow these steps to submit your contributions:

1. Ensure your fork is up to date:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

2. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:
   ```bash
   git add .
   git commit -m "Add a descriptive commit message"
   ```

4. Push your changes to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

5. Create a pull request:
   - Navigate to your forked repository on GitHub.
   - Click "Compare & pull request."
   - Fill in the PR template, providing details about the changes.
   - Submit the pull request.

6. Respond to any feedback or requested changes from reviewers.

---

Thank you for contributing!

