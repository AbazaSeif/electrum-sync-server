#### Electrum sync server
This is the server component for the [Bitcoin wallet Electrum](electrum.org)'s label synchronization feature.

There is a public node available at http://sync.bysh.me:8080/.


##### Installation

###### Docker
A Docker file is included in the repository. You can pull it using `docker pull electrum-sync-server` and then start it using `docker run --rm -v $PWD:/data electrum-sync-server`. You can change $PWD to a folder where you want to save the database file on the host.

###### Source
This project is 'go get(able)' [install Go](http://golang.org/doc/install) and do `go get -u github.com/maran/electrum-sync-server`.
