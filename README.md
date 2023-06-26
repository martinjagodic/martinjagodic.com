# My website

My place on the web: https://martinjagodic.com/

## Installing

You need Hugo installed on your machine: <https://gohugo.io/getting-started/quick-start/>

This repository is set up to be developed with [Visual Studio Code](https://code.visualstudio.com/) editor. Please install reccommended extensions listed in [extensions.json](.vscode/extensions.json)

If this is your first time running the project, run

`npm install` and `npx husky install`

When you have that run one of these commands for local dev server:

`hugo server` or `npm run dev`

and open your local site on http://localhost:1313/

## Development

Follow [BEM](http://getbem.com/) naming convention for CSS class names.

Follow the standard Javascript style.

### Linters

There are 3 linters set up:
- [stylelint](https://stylelint.io/) for CSS
- [eslint](https://eslint.org/) for JS
- [htmlhint](https://htmlhint.com/) for HTML

If quick fixes are possible, VS Code will fix them on save. A pre-commit git hook is also in place. It triggers all 3 linters on staged files, and if there are errors, it prevents the commit.

## Built With

* [Hugo](https://gohugo.io/)
* [Netlify CMS](https://www.netlifycms.org/)
* [Netlify](https://www.netlify.com)
