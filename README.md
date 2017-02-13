# OpenShift Example - Simple Swift
:memo: Swift application example

BUILD (using [swift-s2i](https://github.com/dudash/s2i-swift)):
``` 
> s2i build https://github.com/dudash/openshiftexamples-simpleswift.git dudash/swift-30-ubuntu14 simple-swift 
```

RUN:
```
> docker run simple-swift
```
