build:
#   go micro插件生成
	protoc --proto_path=. \
	  --micro_out=./ \
	  --micro_opt=paths=source_relative \
	  	user.proto
#	原生生成
	protoc --proto_path=./ \
	  --go_out=./ \
	  --go_opt=paths=source_relative \
	  	user.proto