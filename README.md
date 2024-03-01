# System Engineering Devops - Web infrastructure design
![_35e9c4c6-7041-48b5-99bb-2f41364febfd](https://github.com/savvyh/holbertonschool-system_engineering-devops/assets/139894873/0c0b6546-878c-45e9-a1e2-dc9d609b49c6)

## General 🏴
Have to be able to draw a diagram representing the web stack I've built, explain the role of each component, and understand key concepts such as SPOF (Single Point of Failure) and QPS (Queries Per Second). This project will help to solidify knowledge and gain a better understanding of computer system architecture.
This project covers various fundamental concepts related to networks and servers. 
Here are the concepts :
- Network basics
- Web servers
- Application servers
- DNS
- Load balancers
- Monitoring
- Databases
- Network security with HTTPS and firewalls.

## Requierements 👮
- For the following tasks, insert the link from the screenshot into the answer file.
- Cover what the requirements mention.
- Draw a diagram representing the web stack.

## Tasks 💠
0. Simple web stack
    - Requirements:
      * 1 server
      * 1 web server (Nginx)
      * 1 application server
      * 1 application files (your code base)
      * 1 database (MySQL)
      * 1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8

![web](https://github.com/savvyh/holbertonschool-system_engineering-devops/assets/139894873/5295da54-4d7c-4198-939e-134758816710)

1. Distributed web infrastructure
    - Requirements:
      * 2 servers
      * 1 web server (Nginx)
      * 1 application server
      * 1 load-balancer (HAproxy)
      * 1 set of application files (your code base)
      * 1 database (MySQL)

![Design sans titre](https://github.com/savvyh/holbertonschool-system_engineering-devops/assets/139894873/215a365b-2049-415b-ac2a-0a98d3994225)

2. Secured and monitored web infrastructure
    - Requirements:
      * 3 firewalls
      * 1 SSL certificate to serve www.foobar.com over HTTPS
      * 3 monitoring clients (data collector for Sumologic or other monitoring services)

3. Scale up
    - Requirements:
      * 1 server
      * 1 load-balancer (HAproxy) configured as cluster with the other one
      * Split components (web server, application server, database) with their own server

### Authors 🧞‍♀️
Sarah Boutier