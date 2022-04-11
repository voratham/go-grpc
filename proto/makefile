
gen-grpc:
	protoc *.proto --go_out=../server --go-grpc_out=../server
	protoc *.proto --go_out=../client --go-grpc_out=../client

evans-calculator:
	evans --proto=calculator.proto

evans:
	evans -r