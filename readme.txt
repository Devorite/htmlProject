How to Work fast

For work space

npm install gulp-cli -g

1. create new folder of project
2. Copy this package.json
3. Create SRC and BUILD Folder  >>>  mkdir -p src/{html,images,js,scss} build/assets/{images,js,css}
4. run command  npm install
5. gulp


For live Monitor

npm install -g browser-sync

and run 

cd PATH_TO_PROJECT/build/

browser-sync start --server --files "assets/css/*.css" --files "assets/js/*.js" --files "assets/images/*" --files "*.html"