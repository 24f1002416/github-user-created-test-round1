# github-user-created-test

## Summary
Publish a Bootstrap page with form id='github-user-test' that fetches a GitHub username, optionally uses ?token=, and displays the account creation date in YYYY-MM-DD UTC inside #github-created-at.

## Setup
This is a static web application. No build step required.

## Usage
1. Clone the repository
2. Open `index.html` in a web browser
3. Or deploy to GitHub Pages for online access

## Code Explanation
This application implements the following features:
- document.querySelector('#github-user-test').tagName === 'FORM'
- Page has #github-created-at element
- !!document.querySelector("script").textContent.includes('https://api.github.com/users/')

## License
MIT License - See LICENSE file for details
