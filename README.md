Matrix Testing & Conditional Build Assignment

This project demonstrates a GitHub Actions workflow with matrix testing and conditional builds to ensure Node.js project stability and quality.

FEATURES:

- Matrix testing across Node.js versions 16, 18, and 20
- Runs on every pull request and push to main or dev branches.
- Runs nightly at 1 AM UTC on Node current and Ubuntu, generating `test-results/results.json`.
- Conditional build on main branch or version tags
- Artifact storage for test results and build outputs
- Manual approval before publishing (optional)
- Scheduled nightly tests
- Workflow dispatch with skip build option

HOW TO SETUP:

1. Clone the repository
git clone <https://github.com/bhagwandas786/Matrix-Testing-Conditional-Build.git>
cd <Matrix-Testing-Conditional-Build.git>>

2. Install dependencies
npm install

3. Run tests
npm test

4. Build the project
npm run build

RESULTS: 
Action URL:https://github.com/bhagwandas786/Matrix-Testing-Conditional-Build/actions/runs/17851086827
<img width="1368" height="369" alt="image" src="https://github.com/user-attachments/assets/d90fead1-2cb6-4e29-8304-c408fb4d446f" />

SUMMARY:
This workflow ensures the project remains reliable, compatible, and production-ready, with automated testing, nightly checks, and clear reporting of artifacts.
