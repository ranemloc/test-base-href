# TestBaseHref

Deploy to GitHub pages: `npm run deploy`

Check deployment status: https://github.com/ranemloc/test-base-href/deployments

See running app: https://ranemloc.github.io/test-base-href/


## What was done in this repo:

The goal is to have an simple web that runs under a different path under https://ranemloc.github.io

- Created an angular app: `npx -p @angular/cli ng new test-base-href`
- Created a repo in GitHub with the same name as the app, i.e. `test-base-href`
- Set the origin and pushed the code to GitHub
- Added library https://github.com/angular-schule/angular-cli-ghpages by running `ng add angular-cli-ghpages`
- Added a `deploy` script to `package.json` to run the deployment `ng deploy --base-href=/test-base-href/`
