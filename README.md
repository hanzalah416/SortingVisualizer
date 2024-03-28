# Sorting Visualizer
Project Hosted at https://hanzalah416.github.io/Sorting_Visualizer

If you are interested in contributing or providing suggestions please make a pull request or add as an issue.

Hosted on github via gh-pages

### Github Hosting
### `npm run deploy`
Step1: Install github pages by `npm install gh-pages`\
Step2: in package.json add "homepage" attribute example(https://username.github.io/repositoryName). \
Step3: in package.json replace scripts attribute by following lines\
"scripts": {\
		&emsp; "start": "react-scripts start",\
		&emsp; "build": "react-scripts build",\
		&emsp; "test": "react-scripts test",\
		&emsp; "eject": "react-scripts eject",\
		&emsp; "predeploy": "npm run build",\
		&emsp; "deploy": "gh-pages -d build"\
	},\
Step4: in command line run `npm run deploy`
Check in pages settings your repo will be hosted .
\\

