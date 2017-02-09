# vanillaframework.io

Brochure and docs site for Vanilla Framework.

This site relies on the documentation in Markdown format that lives in the Vanilla Framework project.

You can pull these docs in one of two ways:


## 1. Importing docs from local copy of Vanilla Framework.

If you wish to make iterative changes to Vanilla Framework source code and then preview locally, you'll want to link this project to your local copy of the Vanilla Framework project.

1. CD into your Vanilla Framework folder on your machine and run `npm link`

2. Drop back into this folder and run `npm link vanilla-framework`

3. This project will now reference your local copy of Vanilla Framework instead of the global NPM module.

4. If you open two separate Terminal windows for each project and make sure they are installed with `npm install`. Once installed run `gulp develop` in both - any changes you make to Vanilla Framework should be immediately reflected in this project at `http://localhost:3000`

License
---

The content of this project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/), and the underlying code used to format and display that content is licensed under the [LGPLv3](http://opensource.org/licenses/lgpl-3.0.html) by [Canonical Ltd](http://www.canonical.com/).

With ♥ from Canonical.
