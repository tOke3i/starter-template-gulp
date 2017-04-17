# starter-template-gulp
My starter template with Gulp

Install:

git clone git@github.com:tOke3i/starter-template-gulp.git

 Then in project folder open terminal and write: npm i.

Usage:
npm start (and work).

____________________________________________________________________________________________
Production build(all minified):
gulp production (generates folder 'build' in the root foolder of you project)

____________________________________________________________________________________________
Development and tests(no minifies) build:
gulp dev-build (generates folder 'build' in the root foolder of you project)


build/  			There is you project builds (after `gulp production`)
dev-build/  		There is you project builds (after `dev-build`)
app/        		Source folder (livereload works from there)
app/fonts/  		Projects fonts ( 'build/fonts' or 'dev-build/font' it depends of your task)
app/img/    		Images of the project
app/js/     		Global js-files)
app/sass/   		Styles: @include here all you scss files 'style.scss'!
app/index.html      Main page ('app/html/index.html' )
