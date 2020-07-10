# contribution-guide

## Before starting
- If you are new to Git and/or GitHub, email us at [teamfalcon@elevatethefuture.org](mailto:teamfalcon@elevatethefuture.org)
- Accept the email invitation to join the ETF GitHub organization
- Create a repo
  - The name should be all-lowercase, and words should be separated by hyphens (e.g. `mbs-place`, `my-restaurant`)
- Enable GitHub Pages on the repo _(Settings — GitHub — Source — “master branch / docs folder”)_

## Getting started
- Write a short **README.md** in the root of the repo about the site
- Start building the site in your project folder!
	- Write good, [DRY](https://en.wikipedia.org/wiki/Don't_repeat_yourself) code (e.g. comment when necessary)
	- Place all the files for your project in a folder with the same name as your repo (e.g. **mbs-place** for a repo named `mbs-place`)
		- This will be called the project folder
	- Make the entry point for your site **index.html** in your project folder
	- Students should be able to reproduce your site without JS
- Commit often, and make your commit names *descriptive* (e.g. `Scaffolded landing page`, **not** `Added stuff`).
	- Your commits should use sentence case (first word capitalized, all other words lowercase unless necessary)
	- Multi-line commit descriptions are encouraged where appropriate

## Deploying
**Only** when you are finished with your 1st, 2nd, or final draft:
- Make a copy of your project folder in your root directory and rename that folder **docs**
	- If you are using a framework such as Vue (or React) or a static site generator (such as Jekyll), search online for instructions to deploy to GitHub pages (most static site generators have instructions in their docs)
- Commit and push your changes
- View your deployed site at `https://elevate-the-future.github.io/your-repo-name/`

## Finished
- Notify the leads!
- After your website is hosted and the domain is set up, you should delete the **docs** folder.

## File structure
```
 my-repo-name
    ├── README.md
    ├── docs                         # Will be deployed to GitHub Pages (copy of project folder)
    │   ├── about.html
    │   ├── assets
    │   │   └── background.png
    │   ├── contact.html
    │   ├── index.html
    │   └── style.css
    └── my-repo-name                 # Project folder (the contents will vary)
        ├── about.html
        ├── assets
        │   └── background.png
        ├── contact.html
        ├── index.html               # Entry point
        └── style.css
```
