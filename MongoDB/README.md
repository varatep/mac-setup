#installation

brew update

##binaries:
brew install mongodb

##ssl support:
brew install mongodb --with-openssl

##development release:
brew install mongodb --devel

##set up directory for mongod
mkdir -p /data/db

##ensure read/write permissions for /data/db

#usage

mongod to start instance
mongo to connect to instance
