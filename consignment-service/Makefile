build:
#	protoc --proto_path=. --go_out=proto/consignment/ --micro_out=./ \
#    		proto/consignment/consignment.proto
	protoc --proto_path=./ \
        --go_out=./ \
        --go_opt=paths=source_relative \
	  consignment.proto
	protoc --proto_path=./ \
		--go-grpc_opt=require_unimplemented_servers=false --go-grpc_out=. \
        --go-grpc_opt=paths=source_relative \
	  consignment.proto

