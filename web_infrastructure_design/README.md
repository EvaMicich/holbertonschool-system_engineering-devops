# Web Infrastructure Design

This project focuses on the design of a web infrastructure with various levels of complexity, scalability, security, and monitoring. It's designed to provide a solid foundation in understanding the components of web infrastructure and how they interact.

## Concepts

The project covers various concepts including:

- Network basics
- Server
- Web Server
- DNS
- Load balancer
- Monitoring

## Learning Objectives

By the end of this project, you should be able to explain:

- The web stack you built with the sysadmin/devops track projects
- The roles of each component in your infrastructure
- System redundancy
- Acronyms like LAMP, SPOF, QPS

## Project Tasks

Use whiteboarding for tasks

### 0. Simple Web Stack

Design a simple one server web infrastructure hosting a website, www.foobar.com, including the following components: server, web server (Nginx), application server, database (MySQL), domain name. You must be able to explain the roles of each component and identify the potential issues with this setup.

### 1. Distributed Web Infrastructure

Design a three server web infrastructure hosting www.foobar.com, adding additional servers, a load-balancer (HAproxy), application files, and a database (MySQL). You need to explain the roles and reasons for adding each new element, how the load balancer works, the difference between Active-Active and Active-Passive setups, and how a database Primary-Replica cluster works.

### 2. Secured and Monitored Web Infrastructure

Enhance your three server web infrastructure with added security and monitoring capabilities. This includes implementing firewalls, serving traffic over HTTPS with an SSL certificate, and adding monitoring clients. You need to explain the reasons for adding these components and any potential issues that could arise.

### 3. Scale Up

Finally, scale up your infrastructure by adding an additional server and load-balancer, configured as a cluster. Also, split components (web server, application server, database) onto their own servers. You should be able to explain the reasons for these changes.

