
https://user-images.githubusercontent.com/83821864/118033541-c8d8b180-b31d-11eb-8ef0-82fe27d89b39.mp4

its a bash script for tool automation(inspired by nahamsec)

requirements >

1. install go: for linux click here https://golang.org/dl/go1.16.4.linux-amd64.tar.gz

2. setup go (many ways but i like this method)

go to the download directory and copy paste it

sudo tar -xzvf (go downloaded file) -C /usr/local/

cd

mkdir go

cd go

mkdir bin pkg src

cd

vim .profile


copy paste this code in the last line in .profile

> export GOPATH=~/go

> export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin

> save it.
 
type this in terminal

> source .profile (your good to go)

> bash diwu.sh (without root)
