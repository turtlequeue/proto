# Turtlequeue-proto

# Why

Turtlequeue uses GRPC and protobuf to exchange messages. These are the definitions shared by all the SDKs.
See example uses in the Java SDK.

# Develop

Intall maven and run:
```
mvn clean compile install &&  mvn -f admin-pom.xml clean compile install
```

# Javascript
guid:
https://medium.com/blokur/how-to-implement-a-grpc-client-and-server-in-typescript-fa3ac807855e


https://www.xolstice.org/protobuf-maven-plugin/compile-js-mojo.html
https://www.npmjs.com/package/protobufjs

https://www.npmjs.com/package/protobufjs#installation
compile .proto to json?

better - generate ahead-of-time:
https://github.com/grpc/grpc-node/tree/master/packages/grpc-tools


typescript
https://github.com/grpc/grpc-node/blob/v1.7.x/packages/grpc-native-core/index.d.ts
