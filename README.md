## Microservice Deployment Using Multiple Virtual Machines

This project demonstrates a simple Flask-based microservice deployed on a backend
virtual machine and accessed from a client virtual machine using Oracle VirtualBox.

### Virtual Machines
- Backend VM (Ubuntu 22.04): Hosts Flask REST API
- Client VM (Ubuntu 22.04): Accesses backend using curl

### Network Configuration
- NAT networking was used for both VMs.

### Microservice
The backend VM runs a Flask application exposing a REST endpoint on port 5000.
The client VM communicates with the backend using its private NAT IP.

### Screenshots
All implementation evidence is available in the `screenshots/` directory.
