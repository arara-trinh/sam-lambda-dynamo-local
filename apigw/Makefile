PHONY: deps clean build

deps:
	go get -u ./...

clean: 
	rm -rf ./lambdab/lambdab # 変更
	
build:
	GOOS=linux GOARCH=amd64 go build -o lambdab/lambdab ./lambdab/main.go # 変更
