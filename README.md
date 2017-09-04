# 快速使用
获取 mqantserver：

	git clone https://github.com/GodSlave/mqantserver

# GOPATH 用法

GOPATH 用法可以看这边文章[GOPATH 用法](http://www.mqant.com/topic/597714ca8f2e454b2eb1c1ee)

# mqantserver 依赖库

	go get github.com/gorilla/mux
	go get github.com/gorilla/websocket
	go get github.com/streadway/amqp
	go get github.com/golang/protobuf
	go get github.com/golang/net/context
	go get github.com/gogo/protobuf
	go get github.com/opentracing/basictracer-go
	go get github.com/opentracing/opentracing-go
	go get github.com/yireyun/go-queue
	go get github.com/eclipse/paho.mqtt.golang
	go get github.com/GodSlave/mqant
	go get github.com/garyburd/redigo
	go get sourcegraph.com/sourcegraph/appdash
	go get sourcegraph.com/sourcegraph/appdash-data

	
# go get golang.org/x/net 安装失败处理方案

[见GOPATH用法这边文章](http://www.mqant.com/topic/597714ca8f2e454b2eb1c1ee)

## 编译 mqantserver：

> 如果编译过程中提示缺少某个三方库的话通过 go get 命令安装即可

### 将mqantserver根目录设置到GOPATH

[请参考原README](https://github.com/liangdas/mqantserver)