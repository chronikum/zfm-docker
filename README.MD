# ZfM Docker

This is the ZfM-Ausleihsystem as docker-compose.
Images may be out of date.
Last update: 3. June 2021

GNU GENERAL PUBLIC LICENSE V3.0  

## Usage

Clone the repository. Edit the docker-compose.yml, as example, configure the HOST_API.
Make sure you have docker and docker-compse installed.  

``docker-compose up -d``


Info: You can run the system against an nginx reverse proxy and use letsencrypt to secure the connection with tls!
