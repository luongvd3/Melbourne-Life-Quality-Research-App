# Melbourne Quality of Life Research App
This project is designed to be deployed on an OpenStack cloud service

## Requirements
python 3.8.9 \
ansible 2.9

## Set up .env file 
Please create a .env file using the following variable names.  
Replace IP and PORT with the actual IP address and Port number of the couchDB node  

DEBUG=TRUE  
FLASK_ENV=development  
DB_URL=http://%s:%s@IP:PORT/  
DB_USERNAME=  
DB_PASSWORD=  
TWITTER_API_KEY=  
TWITTER_API_KEY_SECRET=  
TWITTER_BEARER_TOKEN=  
TWITTER_ACCESS_TOKEN=  
TWITTER_ACCESS_SECRET=  

## Deployment 
Download the OpenStack RC file from the cloud provider\
Replace './unimelb-COMP90024-2022-grp-24-openrc.sh;' in deployment/run-deployment.sh to the OpenStack RC file\
run /run-deployment.sh
