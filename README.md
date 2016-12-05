# Template: Bootstrap 4 with Gulp

A **basic** template combining:
- Bootstrap 4 (Alpha) with Flexbox
- Sass
- Gulp build tasks including sass compliing, browser sync and css/js concatentation and minification

## Setup

1) Clone the repo

2) Update site details in packages.json (i.e. name, github repo address, etc)

3) Run ```npm install gulp```

4) Run ```npm install --save-dev``` 

## Usage

- Run ```gulp``` to enable watching, which will automatically compile Sass and display changes using Browser Sync
- Develop to your heart's content in the src directory!
- When ready to build distribution files, run ```gulp build```
- If ```gulp build``` fails to correctly clean out the dist directory, run ```gulp clean:dist``` to do it manually, then run the build command again
