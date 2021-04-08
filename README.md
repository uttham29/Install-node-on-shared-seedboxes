# Install-node-on-shared-seedboxes

```
echo 'export PATH=$HOME/local/bin:$PATH' >> ~/.bashrc
. ~/.bashrc
mkdir ~/local
wget http://nodejs.org/dist/node-latest.tar.gz
tar -xvf node-latest.tar.gz
cd *node*
./configure --prefix=~/local
make install -j4
```

> j4 refers to usage of 4 threads, you can use increase or decrease it.
> As you are building it from source installation may take few minutes.
