<!-- ABOUT THE PROJECT -->
## About The Project
Project Name: Udagram

Your company is creating an Instagram clone called Udagram.
Developers want to deploy a new application to the AWS infrastructure.

### Prerequisites

Create key-pair: VocareumUdagramKey.pem

### Installation

1. Run network.yaml file with batch script:
```
./create.sh networkStack ../configs/network.yml ../configs/network-parameters.json
```
2. Run server.yaml file
```
./create.sh serverStack ../configs/server.yml ../configs/server-parameters.json
```

Refer to build/README.md

### URLs
1. elb link
http://serve-webap-kod5rvvoaau0-1429507744.us-east-1.elb.amazonaws.com/
