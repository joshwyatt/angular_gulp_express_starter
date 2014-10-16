angular_gulp_express_starter
============================

This is a very skinny starter repo for building *EAN stack apps with gulp.

##Using

Just fork and clone down the repo and `gulp dev` from inside the root directory.

Gulp tasks are set up to do the following:

  - Run an express server and restart it on changes to your html or js files
  - jsHint all your js files, and jsHint them again when they change
  - Inject script tags for all js files into index.html
  - Live reload your html files open in your web browser when they change 
