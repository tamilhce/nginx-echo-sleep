# nginx-echo-sleep

A simple tool for simulating slow HTTP responses.
The server will be listening in the port 8080
example query format
<ip:8080>/sleep?<sleep_in_seconds>
eg: curl localhost:8080/sleep?1    - wait for 1 sec
    curl localhost:8080/sleep?0.5  - wait for 0.5 sec
For the Docker image, docker pull tamilhce/nginx_echo_sleep
