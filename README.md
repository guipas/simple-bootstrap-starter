# simple-bootstrap-starter
A stupidly simple template to start a project using Bootstrap + Bower + LESS + Gulp

##To start a project : 

###1. Clone this project into your project directory
      git clone https://github.com/guipas/simple-bootstrap-starter.git myproject
      cd myproject
###2. Make sure you have Bower & Gulp installed
      npm install gulp gulp-less bower
###3. Install bootstrap with bower
      bower install --save-dev bootstrap
###4. Launch Gulp (already configured)
      gulp
###5. You are ready to go
Just edit the ./less/custom.less file. The CSS file will be compiled for you in ./css/custom.css (this is the file you will use in your project). For example : 
      \<link rel="stylesheet" href="./css/custom.css"\>
