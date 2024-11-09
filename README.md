# Cloud Student Portfolio


## How to run the Go application:

'''
git clone https://github.com/devIYKE/CLO2003_fall24.git
cd CLO2003_fall24/Week10
go run main.go
'''


## How to build the Cloud Engineer Portfolio Docker image

'''
git pull
docker build -t cloud_portfolio:0.1 .
'''


## How to run the Cloud Engineer Portfolio Docker image

'''
docker run -p 3000:80 cloud_portfolio:0.1
'''

## How to push the image to the Docker Hub

'''
docker login
docker tag cloud_portfolio:0.1 deviyke/cloud_portfolio:0.1
docker push deviyke/cloud_portfolio:0.1
'''
