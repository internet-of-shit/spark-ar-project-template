# Spark AR Project Template
<img src="https://github.com/internet-of-shit/spark-ar-project-template/blob/master/filtericon.png" height="140">
<!-- pshh. change in the url the repository link to your own -->

Comprehensive template for spark-ar projects. Include your models, images and even use npm and webpack to build your scripts. 

## Handy Links
[Spark AR Docs](https://sparkar.facebook.com/ar-studio/learn/documentation/guides/)

### Quickstart

#### I don't need to script

OK then. You'll find a nice folder structure for your project, already filled with the original Spark AR Assets! 
Just save your Spark Project inside "/spark-project/" and have fun!

#### I actually want to script

1. ```npm install``` to install the depencies. 
Use npm to install other plugins. 

2. Do your magic in ```/scripts/script.js```.

3. ```npm run dev``` will watch for changes and copy automagical to ```/spark-project/scripts/```

4. ```npm run build``` will bundle your script, minimize it and paste it to ```/spark-project/scripts/```
