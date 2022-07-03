# gRPC c++ Server using Bazel

This is a basic example for building a service using gRPC on c++

## To Build
```
bazel build //main:hello_project
```

## To Run service
```
./bazel-bin/main/hello_project
```

It will run on port 13000

## Client

I will be add a example for a client, but the main/HelloProto.proto could be used to compile the required libraries on any language using `protoc` to use it on a client.
