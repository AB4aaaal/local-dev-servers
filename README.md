# Development Environment Templates

This repository contains templates for setting up development environments for various technologies. These templates are intended for development purposes only and can be used to quickly spin up instances of different technologies.

## Available Templates

- MongoDB
- Cassandra
- Kafka

## Usage

Each template provides the necessary configuration files to deploy the respective technology in a development environment. Follow the instructions in each template's directory to set up and run the environment on Minikube.

1. Ensure Docker and Minikube are installed and running on your machine.
2. Start Minikube with the command:
   ```
   minikube start
3. Apply the configuration files using kubectl
   ```
   kubectl apply -f <template-file>
4. Expose the service from minikube to use in IDE. To do that run the  following command and use the urls from the output.
   ```
    minikube service --all=true
    


## Requesting New Templates or Improvements

If you have suggestions for improvements or need templates for additional technologies, please create an issue on GitHub. We welcome contributions and feedback from the community to enhance these development environment templates.