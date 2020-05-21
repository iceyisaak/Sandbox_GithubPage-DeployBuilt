# Sandbox_Githubpage-DeployBuild

Test Deploying a general project on Github Page using the `gh-pages package`

source: https://www.youtube.com/watch?v=SKXkC4SqtRk

---

> By installing the **gh-pages**, `gh-pages branch` is created automatically where the page will be created and hosted instantaneously.

### Steps to deploying with gh-pages

1. Run `npm install gh-pages`
2. Add `"deploy": "gh-pages -d dist"` to the Script in the `package.json`
   - the `dist` folder contains files to be deployed on the Github Page
3. Run `npm run deploy`
4. Access the link provided by github pages under `settings > Options > Github Pages`
