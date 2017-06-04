# stackdriver-custommetrics-spring-boot
Set of tools/libraries to deal with Spring Boot metrics and Google Stackdriver

## Motivation
If you run a [java spring boot application](https://projects.spring.io/spring-boot/) in [Google Compute Engine](https://cloud.google.com/compute/) or in [Google Container Engine](https://cloud.google.com/container-engine/) (both parts of [Google Cloud Platform](https://cloud.google.com)) and you want to use [Google Stackdriver](https://cloud.google.com/monitoring/docs/) to monitor it, the only way you have is to create [custom metrics](https://cloud.google.com/monitoring/custom-metrics/). 
On the other hand since the structure of [Spring Boot metrics](http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#production-ready-metrics) is standardized the effort of creating those custom metrics could be shared. 
