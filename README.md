# zuul-performance-test
make a performance test for zuul gateway.

deploy on 6 VPS:
1.eureka

2.spring-config-server

3.zuul

4.service-1

5.service-2

6.test-server

VPS configuration:

1 CPU/1GB memory/10GB data disk

all boot with:nohup java -jar xxx.jar &

test tool:wrk


result:

<img src="https://wx3.sinaimg.cn/mw690/7f366bb3ly1fun740fs55j21hy0v3422.jpg"/>
