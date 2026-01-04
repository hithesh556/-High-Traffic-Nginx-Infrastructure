This repository contains the Infrastructure-as-Code (IaC) for deploying a lightweight, high-performance Web Server using Nginx and Docker Alpine 

- Base Image: Alpine LInux (Securit hardened).
- Server: Nginx	(Optimised for concurrent connection).
- Deployment: Containerized for	portability across AWS/Azure environments.

1. Build: 'docker build	-t server.'
2. Run:	'docker	run -p 80:80 server'
