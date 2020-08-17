#服务网关 Zuul（路由）【Finchley 版】
###需要启动 eureka-server、eureka-producer、eureka-consumer  
###转发到producer服务的请求规则为：/producer/**
###转发到consumer服务的请求规则为：/consumer/**
http://localhost:14000/consumer/hello/?name=yibo
该请求将最终被路由到consumer的/hello接口上