# Static site template

This is a static website generator setup built for crafting simple website projects.

The generator uses markdown and handlebars to produce html-files using metalsmith. Each markdown-file should contain a header linking it to the desired layout-file. Check out src/index.md and src/layout/index.html for reference.

## Usage

- Place html layouts for pages into src/layouts
- Scss anywhere under src/ as per preference.

## Running:
- npm install: Installing dependencies
- npm start: Starts http-server and runs the build scripts
- npm run start-prod: Production deploy, no nodemon-process

License: MIT
