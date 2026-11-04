# Super Agent Test

A disposable test repository for evaluating DeepSeek Super Agent with the TunnelLab setup.

## Purpose

- Test GitHub issue and comment triggers.
- Verify agent-created branches and pull requests.
- Review changes manually before merging.

## Safety

This repository is for experiments only. Do not store API keys, passwords, access tokens, or personal data here. Agent-generated changes must be reviewed before merging.

## Getting started

Use a GitHub issue or comment to describe a small, clearly scoped test task. The agent operates through the dedicated `pouraminam` account, with `pouramin` as the authorized requester.

## Preview the Landing Page

To preview this landing page locally:

1. Ensure you have Git installed
2. Clone this repository:
   ```bash
   git clone <repo-url>
   cd superagent-test
   ```

3. Open `index.html` in your web browser, or serve the page using a local web server:
   ```bash
   # Using Python's http.server
   python3 -m http.server 8000
   
   # Or using Node.js
   npx http-server
   ```

4. Visit `http://localhost:8000` or the corresponding port in your browser to see the landing page.

## Landing Page Features

This repository includes a simple, responsive landing page with:

- A hero section with a call-to-action button
- Three feature cards showcasing key capabilities
- Navigation to different sections
- Modern design with blue and orange accents
- Built using HTML, CSS, and vanilla JavaScript
- Responsive layout for mobile and desktop views

The landing page serves as a demonstration of the Super Agent test environment capabilities.
