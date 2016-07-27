Tutorial
========

Prepare the swift 3.0-pre2 install gzip package for linux(ubuntu 15.10)
--------------------------------------------------------------------

```sh
    cd swift/3.0pre2
    wget https://swift.org/builds/swift-3.0-preview-2/ubuntu1510/swift-3.0-PREVIEW-2/swift-3.0-PREVIEW-2-ubuntu15.10.tar.gz
```

How to build the docker image
-----------------------------

```sh
    docker build -t "swift:3.0-pre2" ./
```

How to run the docker image
---------------------------

```sh
    // run the docker with a bash
    docker run -i -t swift:3.0-pre2 /bin/bash
```

