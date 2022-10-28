# Setup a new project

## Vite

1. open a terminal
2. navigate to the folder
3. `npm create vite@latest` (will create a new folder)
4. cd intoProject
5. `npm install`
6. THEN we open it in VSCode
7. Now we can rtun `npm run dev` or `npm run build`

## Git

1. `git init`
2. `git status` (NO node_modules or dist)
3. `git add --all`
4. `git commit -m "and so it begins"`
5. Shift + Command + P search for Publish to Github

## SASS

1. `npm install --save-dev sass`
2. rename style.css to style.scss
3. Change the import in main.js (from import "./style.css" to import "./style.scss")
4. start writing SASS

## Netlify

1. Sign in/up
2. Add new site => import existing project
3. Pick it from github
4. make sure it says `npm run build` and `dist`
5. when you push, netlify does the rest
