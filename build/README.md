1. How to execute the Shell scripts?
```
./<file_name> argument_1 argument_2 argument_3
```
For example, you can run the following command

```
# Network
./create.sh networkStack ../configs/network.yml ../configs/network-parameters.json
./update.sh networkStack ../configs/network.yml ../configs/network-parameters.json
./delete.sh networkStack

# Server
./create.sh serverStack ../configs/server.yml ../configs/server-parameters.json
./update.sh serverStack ../configs/server.yml ../configs/server-parameters.json
./delete.sh serverStack
```

2. Troubleshoot: to grant the execute permission to the owner
```
chmod +x create.sh
chmod +x update.sh
chmod +x delete.sh
```