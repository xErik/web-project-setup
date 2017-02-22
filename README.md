# Purpose

Create skeleton for website, including Bootstrap, Browserify, local server and automatic rebuild.

The resulting package is set to private and a proprietary license.
Also, the *raw code* of the website is not published to Github, only the compiled result.

The resulting website is meant to be published on Github in the `docs` folder of a repository.

# Prepare

1. Copy the project
2. Adjust settings in `package.json`
3. Adjust settings in `src/html/index.html`
3. Adjust URL in `CNAME`
5. Remove lines from .gitignore:
    * !/package.json
    * !/README.md
    * !/src


# Install

1. `npm i`
2. `npm run build:watch`
3. `npm run build:server`

# TODO

1. Automate setting of parameters.
2. Publish to github via script, which also uglifies JS implicitly.
