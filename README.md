# Main Site touchofspace.co.nz

This is the repository for the main Touch Of Spice website.

This website runs based on the Hugo framework and is intended to be deployed and hosted via Netlify (including Decap CMS) as a serverless web application. Whilst this is a static website there are a number of backed microservices that it interacts with to give it some dynamic components.

# Prerequisites
- VSCODE or other IDE
- Hugo
- Node & NPM
- Git

# Setting Started
Use the deploy button to get your own copy of the repository.
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Art-Science-NZ/touchofspice.co.nz&stack=cms)

This will setup everything needed for running the CMS:

* A new repository in your GitHub account with the code
* Full Continuous Deployment to Netlify's global CDN network
* Control users and access with Netlify Identity
* Manage content with Netlify CMS

Once the initial build finishes, you can invite yourself as a user. Go to the Identity tab in your new site, click "Invite" and send yourself an invite.

You can now add and edit content by navigating to your.app/admin.

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

# Publishing Changes
To push changes live simply commit and push to the main branch and the continuous deployment will take care of the rest.