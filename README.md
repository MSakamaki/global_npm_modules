

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


