Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the index.html file in your web browser.
Advanced Usage

After installation, run npm install and then run gulp dev which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the gulpfile.js to see which tasks are included with the dev environment.
Gulp Tasks

    gulp the default task that builds everything
    gulp dev browserSync opens the project in your default browser and live reloads when changes are made
    gulp css compiles SCSS files into CSS and minifies the compiled CSS
    gulp js minifies the themes JS file
    gulp vendor copies dependencies from node_modules to the vendor directory
    
…or create a new repository on the command line

echo "# agv_relaunch2018" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/rymjo/agv_relaunch2018.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/rymjo/agv_relaunch2018.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
