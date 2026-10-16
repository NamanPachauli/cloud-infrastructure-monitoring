# AWS Cloud Infrastructure & Secure Network Deployment

## Project Overview
This project demonstrates cloud infrastructure learning using LocalStack for AWS service simulation and Docker with Nginx for local web-server deployment.

## Technologies
- AWS CLI
- LocalStack
- Docker
- Nginx
- Windows CMD

## Implementation
1. Configured a local AWS service simulation environment using LocalStack.
2. Used AWS CLI to inspect simulated EC2 resources.
3. Deployed an Nginx web server in a Docker container.
4. Exposed the web server through a local host port for browser-based testing.

## Verification
- Access the Nginx web server at `http://localhost:8081`.
- Check container status using `docker ps`.

## Learning Outcomes
- AWS CLI fundamentals
- Cloud-service simulation
- Docker container deployment
- Basic web-server testing and troubleshooting

**Note:** This project uses LocalStack and local Docker. It does not represent a live deployment on AWS EC2.
