<!-- ABOUT THE PROJECT -->
## About The Project
Project Name: Udagram

Your company is creating an Instagram clone called Udagram.
Developers want to deploy a new application to the AWS infrastructure.

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

### Installation

1. Create key-pair name
2. Run network.yaml file with batch script:
```
./create.sh networkStack ./yaml/network.yml ./yaml-parameters/network-parameters.json
```
3. Run server.yaml file
```
./create.sh serverStack ./yaml/server.yml /yaml-parameters/server-parameters.json
```
4. Enter your API in `config.js`
