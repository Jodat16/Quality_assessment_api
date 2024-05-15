# Quality_assessment_api

Video link :
https://www.youtube.com/watch?v=HyCO6nMdxC0

To build docker image : 
docker build -t qualityassessmentapi-image .

To create docker container out of image and run : 
docker run -d --name qualityassessmentapi-cont -p 8010:8010 qualityassessmentapi-image

To login from our terminal into remote azure container registry(get credentails from access keys of the container registry)
docker login server_url -u user_name -p password  

To build in remote registry
docker build -t registryqualityassessmentapi.azurecr.io/qualityassessmentapi-image . 
