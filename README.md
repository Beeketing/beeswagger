# Install
```sh
go get -u github.com/grpc-ecosystem/grpc-gateway/protoc-gen-grpc-gateway
go get -u github.com/Beeketing/protoc-gen-beeswagger
go install $GOPATH/src/github.com/Beeketing/protoc-gen-beeswagger
```

# Using 
```sh
protoc --beeswagger_out=logtostderr=true:. <proto_path>
```

# Note
Using comment of field (service) for description of this field (service) 