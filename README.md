# jenkins-traffic-light-sender

## TODOs
  * create a registration module for Users ( ID -> user + jenkins jobs to Watch)
  * create a poller which polls a jenkins instance for the current status of the jobs
  * define protocol for send and receive
  * create sender module which send the messages via 433Mhz to the clients
  
## Hardware
  * raspi
  * 433Mhz sender or arduino with 433Mhz sender 
  
  
## Software running on raspi:
  * Jenkins (for status examples)
  * Http or Tomcat Server for running registration module
  * Small Database??
