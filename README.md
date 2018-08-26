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

<img src="http://photo2.fanfou.com/v1/mss_3d027b52ec5a4d589e68050845611e68/ff/n0/0g/7h/qa_59385.jpg@596w_1l.jpg"/>
