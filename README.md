# continuous-benchmarking
Continuous benchmarking with gatling and ELK

## Installing 

From your docker host:

* git clone this project

* Change the host and port of your benchmarking machine into *logstash/config/jmx/logstash-jmx.conf*.

* Start the *docker-compose up*.

This project will process the fake logs file inside the logstash folder, so please change it to pull your real gatling logs.

