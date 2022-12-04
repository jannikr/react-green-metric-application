# React - Green Metric testing

Basic React app ready for Green Metrics Tool

# Docker commands

Build image:

`docker build --target build -f Dockerfile.prod -t build-image`

Run server image:

`docker build --target server -f Dockerfile.prod -t server-image`

Build project and deploy on server:

`docker-compose -f docker-compose.yml up -d --build`

Stop docker:

`docker-compose -f docker-compose.yml down`



