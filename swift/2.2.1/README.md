Tutorial
========

Prepare the swift 2.2.1 install gzip package for linux(ubuntu 15.10)
--------------------------------------------------------------------

```sh
    cd swift/2.2.1
    wget https://swift.org/builds/swift-2.2.1-release/ubuntu1510/swift-2.2.1-RELEASE/swift-2.2.1-RELEASE-ubuntu15.10.tar.gz
```

How to build the docker image
-----------------------------

```sh
    docker build -t "swift:2.2.1" ./
```

How to run the docker image
---------------------------

```sh
    // run the docker with a bash
    docker run -i -t swift:2.2.1 /bin/bash
```

