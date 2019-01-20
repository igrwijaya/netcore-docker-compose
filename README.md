# Docker Compose setup for .NET Core

Feature:
- Docker Registry
- Nginx
- .NET Core web application container

how to use:
- start docker server --> docker-compose -f docker-compose-dev.yml up -d
- stop --> docker-compose -f docker-compose-dev.yml down
- stop registry --> docker-compose -f docker-compose-dev.yml stop registry
- start registry --> docker-compose -f docker-compose-dev.yml start registry

Just for my personal documentation. If you want to ask anything about this setup, please email me to me@igrwijaya.id

create ssl here --> https://www.sslforfree.com
then download .zip ssl files
upload to folder certs
nano certificate.crt --> add more whitespice at the bottom
cat certificate.crt ca_bundle.crt > server.crt