Jastrzebowski.pl
==========

New http://jastrzebowski.pl website. Development preview on http://dev.jastrzebowski.pl/jastrzebowski

## Setting up development environment 
1. Install [node.js](http://nodejs.org) on your system. 
2. Clone this repository, open console and go to its directory. 
3. Install [grunt-cli](https://github.com/gruntjs/grunt-cli) globally on your system by typing `npm install -g grunt-cli`. 
4. Type `npm install` to download all dependencies necessary by project. 
5. Run `grunt` command and have fun! 

* You can use [LiveReload](http://livereload.com) plugin for [Chrome](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei) or [Firefox](https://addons.mozilla.org/pl/firefox/addon/livereload/) and stop refreshing your browser ;)

## Building site to production
1. Latest version should be actually build in `dist/` directory. 
2. After your work is done, stop `grunt` runner and type `grunt build`. 

## Deploying site to server

If you want to quickly deploy your site to server, you have to **always build project first**. 

1. Please edit `Gruntfile.js` and find `scp` task options. 
2. Set up your SSH access and server path. 
3. Upload site by running `grunt deploy` command. 
