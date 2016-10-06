# Go Installing

## Download [Go](https://golang.org/dl/)

## Extract tarballs
```
sudo tar -C /usr/local -xzf go1.7.1.linux-amd64.tar.gz 
```

## Make Works Directory
```
mkdir -p $HOME/Works/go/{src,pkg,bin}
```

## Add Env Vars.
```
export PATH=$PATH:/usr/local/go/bin
export GOPATH=$HOME/Works/go
export PATH=$PATH:$GOPATH/bin
```

## Install Go Commands
```
go get golang.org/x/tools/cmd/...
```
