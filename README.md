# VCC_MultipleVMs
This repository demonstrates deployment of a simple microservice application across multiple VirtualBox virtual machines using NAT networking.

# Microservice Deployment Using Multiple Virtual Machines

## Objective
The objective of this project is to demonstrate the deployment of a simple microservice application across multiple virtual machines using Oracle VirtualBox.

## Environment Setup
- Host OS: Windows
- Virtualization Tool: Oracle VirtualBox
- Guest OS: Ubuntu 22.04 LTS
- Networking Mode: NAT
- Backend VM IP: 10.0.2.15
- Client VM IP: 10.0.2.x

## Architecture Overview
- Backend VM hosts a Python Flask microservice.
- Client VM sends HTTP requests to the backend service.
- Communication happens over NAT network using private IPs.

## Backend Service
The backend service is a simple REST API implemented using Flask.

### Endpoint

### Sample Response
```json
{
  "service": "backend",
  "status": "running"
}
sudo apt update
sudo apt install python3-pip -y
pip3 install flask
python3 app.py

curl http://10.0.2.15:5000

