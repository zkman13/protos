 protoc -I ./proto --go_out=paths=source_relative:./gen/go --go-grpc_out=paths=source_relative:./gen/go ./proto/sso/sso.proto

 work work