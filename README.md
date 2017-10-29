# Dev stack starter kit
This is a basic project structure for any kind of application using Gulp build system.

### Clone this structure via command line to your laptop:

    git clone https://github.com/MarekJCK/blankProjectSetup.git
    
    1. Rename it (mv blankProjectSetup newName)
    2. CD into it.
    3. Delete .git directory ($ rm -rf .git* )
    
### Go to [github](https://github.com/) and create new repository with the name you rename the clone.
    
     Create a new repository on command line:
    
        git init
        git add .
        git status (you see all the files you cloned has been added)
        git commit -m "first commit"
        git remote add origin https://github.com/MarekJCK/Repository-name.git
        git push -u origin master

### .gitignore

    create your unique .gitignore file:

    .idea/**/workspace.xml
    .idea/**/tasks.xml
    .idea/dictionaries

    .idea/
    node_modules/
    .DS_Store
    .sass-cache


### NPM & Gulp

1.  You will need Node.js' package ecosystem, npm. So install [Node.js](https://nodejs.org/en/).
2. **Create package.json:**                          `$ npm init`
3.  **Install Gulp global:**                         `$ npm install --global gulp`  
4.  **Install Gulp as devDepencency:**               `$ npm install --save-dev gulp`
5.  **Install Normalize.css as Dependancy:**         `$ npm install --save normalize.css`

6. **Install other gulp dependencies:**
    **USE *sudo* IF NEEDED**
    
    ```
    sudo npm install gulp-sass --save-dev gulp-minify-css --save-dev gulp-webserver --save-dev gulp-watch --save-dev gulp-uglify --save-dev pump --save-dev
    ```
7. **Run gulp:**  `$ gulp`
8. _Clear this readme_

