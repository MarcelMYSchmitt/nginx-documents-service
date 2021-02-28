# Information

Simple Setup of NGINX for deploying documents as separate service.  
You can find the setup for the docker image inside `docker` folder and next to it the regarding deployment kubernetes chart inside `kubernetes` folder.

Locally (by using docker-compose) the two test pdfs will be availalable under: 
- localhost:1234/test1.pdf
- localhost:1234/test2.pdf

All other requests will lead (error handling) to google.com.  
You will find this all definied inside the `nginx.conf`. 


## What's missing?

There is no ingress or virtual service file inside this repository. 