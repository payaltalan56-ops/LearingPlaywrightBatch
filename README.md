# Learning Playwright Batch

Playwright examples and exercises used for learning and demonstrations.

Repository structure
- chapter_01_Basics/ — basic Playwright examples and quick tests
  - 01_verify_setup.js
  - 02_hot_code.js
- chatper_02_java_concept/ — (empty or Java-related exercises)

Quick start
1. Install Node.js (v16+ recommended) and Git.
2. From the repository root, install Playwright and test runner:

   npm install --save-dev @playwright/test
   npx playwright install

3. Run tests:

   npx playwright test

4. Open an HTML report (after tests run):

   npx playwright show-report

Notes
- This repo includes example scripts; adapt package.json scripts as needed.
- .gitignore is present to exclude node_modules, Playwright artifacts, and editor files.

License
This project has no license specified. Add a LICENSE file if required.
