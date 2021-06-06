# ZfM Docker

This is the ZfM-Ausleihsystem as docker-compose. The docker images are being built automatically and are always up to date.
This wasn't tested 100% - be aware you are running a beta software.
If you have problems, feel free to open an issue in ausleihsystem-frontend.

## Usage

Clone the repository. Edit the docker-compose.yml, as example, configure the HOST_API.

``docker-compose up -d``

> Info: You can run the system against an nginx reverse proxy and use letsencrypt to secure the connection with tls!

## Lizenzinformationen

Licensed: GNU GENERAL PUBLIC LICENSE V3.0   
Developed and maintained by Jonathan Fritz (Zentrum für Medienbildung, Pädagogische Hochschule Schwäbisch Gmünd).
