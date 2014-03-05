

## ubuntu nodejs install memo

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


