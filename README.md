# nginx-echo-sleep

A simple tool for simulating slow HTTP responses.<br />
The server will be listening in the port 8080<br />
example query format<br />
<ip:8080>/sleep?<sleep_in_seconds> <br />
eg: curl localhost:8080/sleep?1    - wait for 1 sec<br />
    curl localhost:8080/sleep?0.5  - wait for 0.5 sec<br />
For the Docker image, docker pull tamilhce/nginx_echo_sleep<br />
