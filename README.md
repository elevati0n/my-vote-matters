# my-vote-matters

To run:
```
cd my-vote-matters
python -m SimpleHTTPServer 8080
```
Sean AF Note: .

By using the following ruby libraries 

'bootstrap-sass'
'compass'

gem install bootstrap-sass
gem install compass

I have set up this project to use the CSS compilation tool Compass.

and to be able to compile and minify our own SASS, allowing us to cache and have greater 
control over our styling.

I have changed the config.rb file to work with our existing directory structure.  

The main.scss file located in te sass folder is identical to how main.css was before.

Just edit it in the sass folder to take advantage of sass, and then use 

compass compile 

to output the updated css/main.css 

to ease development, you can run compass watch and everytime a CSS file is editted it will automatically recompile.

minifiying can be specified at compile time via the CLI or ahead of time in the config.rb file.  



