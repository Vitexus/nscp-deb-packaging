# NSClient++ deb packaging (beta)

build dependencies:

```
apt-get install git cmake build-essential python-dev libssl-dev libboost-all-dev libprotobuf-dev protobuf-compiler python-protobuf libcrypto++-dev liblua5.1-0-dev libgtest-dev libssl-dev ruby-dev 

gem install fpm


```

there's also documentation which is generated by following libraries:
```
apt-get install rst2pdf
```

building specific branch

```
$ ./build_nscpp --repo https://github.com/mickem/nscp.git?branch=0.4.2
```

