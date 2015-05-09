Tapfuse.github.io
=================
http://tapfuse.github.io/



Page source repository
=======================================
https://github.com/TapFuse/TapFuse-site


### Install Harp server
` sudo npm install -g harp`
More info: http://harpjs.com

#### RUN:
Inside project folder run `harp server` this will create a basic HTTP server and compile all *.jade* and *.less* files on the fly. By default you can access the site at `http://localhost:9000/`

#### COMPILE:
Inside project folder run `harp compile ./ ../tapfuse.github.io` this will create a `tapfuse-github.io` folder with html file and all the assets required to deploy the site.

#### TEST:
You can run `harp server` inside the `tapfuse.github.io` folder to test the site locally.

#### DEPLOY:
Use GitHub app to deploy updated page content to GitHub pages
