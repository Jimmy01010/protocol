build:
#	protoc --proto_path=. --go_out=proto/consignment/ --micro_out=./ \
#    		proto/consignment/consignment.proto
	protoc --go_out=./ \
	  ./consignment.proto
	protoc --go-grpc_opt=require_unimplemented_servers=false --go-grpc_out=./ \
	  ./consignment.proto

