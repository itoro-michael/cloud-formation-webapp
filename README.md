# Deploy a High-Availability Web App using CloudFormation



![Infrastructure diagram](https://github.com/itoro-michael/cloud-formation-webapp/blob/main/udagram_network.jpg?raw=true)

AWS Network and Server Infrastructure Diagram:

## Files in the project:

1. network.yml: Yaml file defining the network structure of the project.
2. network-parameters.json: Json file housing the parameter values of network.yml.
3. servers.yml: Application config file.
4. server-parameters.json: App parameter values.
5. run.sh: Deployment script.
6. udagram_network.jpg: The infrastructure diagram.


## Usage examples:

-  `./run.sh deploy us-east-1 udagram-servers servers.yml server-parameters.json`   
-  `./run.sh preview us-east-1 udagram-servers servers.yml server-parameters.json`  
-  `./run.sh delete us-east-1 udagram-servers`