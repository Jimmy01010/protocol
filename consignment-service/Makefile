build:
	protoc --proto_path=. \
	  --micro_out=./ \
	  --micro_opt=paths=source_relative \
	  	consignment.proto
	protoc --proto_path=./ \
        --go_out=./ \
        --go_opt=paths=source_relative \
	  consignment.proto
#	protoc --proto_path=./ \
#		--go-grpc_opt=require_unimplemented_servers=false --go-grpc_out=. \
#        --go-grpc_opt=paths=source_relative \
#	  consignment.proto

