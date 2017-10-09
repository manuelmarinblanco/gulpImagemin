# gulpImagemin
Minify PNG, JPEG, GIF and SVG images with imagemin

Firsts steps:
https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md

Fixing permission errors:
https://docs.npmjs.com/getting-started/fixing-npm-permissions

    sudo chown -R yourUsername /usr/local/bin
    sudo chown -R yourUsername /usr/local/lib/node_modules/
    sudo chown -R yourUsername /usr/local/share/

    sudo chown -R yourUsername /usr/yourUsername/node_modules
    
    From the project folder, without sudo:
    npm install --save-dev gulp-imagemin 
    
    Don't forget change the permissions of your project folder
    sudo chown -R yourUsername /routeToYourProjectFolder
