

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
npm i -g npm-check-updates
# dev tools
npm i -g yo grunt-cli bower
npm i -g jspm webpack
npm i -g gulp slush
# testing tools
npm i -g karma-cli
npm i -g protractor elementor appium
npm i -g istanbul
# alt js
npm i -g typescript
# document
npm i -g jsdoc
# node debug tools
npm i -g node-inspector devil
# hybrid
npm i -g cordova reapp
# others
npm i -g hexo
npm i -g forever

```


