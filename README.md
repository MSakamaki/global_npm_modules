

## ubuntu nodejs install memo


#### 前提

 + g++
 + git

  ``sudo  apt-get install git g++``

node install

url get [node.org/dist/](http://nodejs.org/dist/)

```sh

./configure --prefix=$HOME/local/node
make
sudo make install
```

add .bashrc

```sh

export PATH=$HOME/local/node/bin:$PATH
```

node uninstall

```sh

cd $HOME/local
rm -r node
```

my npm modules

```sh
# dipendency
npm i -g npm-check-updates bower-check-updates
# dev tools
npm i -g jpm
npm i -g yo grunt-cli bower
npm i -g jspm webpack
npm i -g gulp slush
# testing tools
npm i -g karma protractor elementor appium nightwatch istanbul
# alt js
npm i -g typescript tsc
# document
npm i -g jsdoc esdoc yuidocjs
# node debug tools
npm i -g node-inspector devil
# lint
npm i -g jshint eslint jscs
# hybrid
npm i -g electron-prebuilt # cordova reapp 
# vim
npm i -g instant-markdown-d
# others
npm i -g hexo mermaid forever http-server
npm i -g esprima babel rollup

```


