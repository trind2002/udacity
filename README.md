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
2. lucidchart
https://lucid.app/lucidchart/c02c785b-845f-4d33-a2b6-3f3c3537e5ec/edit?viewport_loc=-1898%2C-3766%2C3660%2C1674%2C0_0&invitationId=inv_ab96e0d9-67ee-4555-8609-b8ecf9271996

