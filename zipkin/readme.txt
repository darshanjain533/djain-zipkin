Run all the 4 servers
download and install zipkin jar - zipkin-server-2.23.18-exec.jar

java -jar zipkin-server-2.23.18-exec.jar

the server will be start at 9411

hit the url http://localhost:8081/zipkin

goto zipkin and you would see the trace ID generated. this trace id has 4 span id as per the logic written. 