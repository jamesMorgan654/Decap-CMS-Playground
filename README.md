# Main Site touchofspace.co.nz

This is the repository for the main Touch Of Spice website.

This website runs based on the Hugo framework and is intended to be deployed and hosted via Netlify (including Decap CMS) as a serverless web application. Whilst this is a static website there are a number of backed microservices that it interacts with to give it some dynamic components.

# Prerequisites
- VSCODE or other IDE
- Hugo
- Node & NPM
- Git

# Running Locally
1. Clone Repository
2. Initialise project directory
```bash
npm init
npm install --save
```
3. Run server locally
```bash
hugo server -D --disableFastRender
```
4. To push changes live simply commit and push to the main branch.