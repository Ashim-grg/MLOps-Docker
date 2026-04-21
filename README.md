* Assure that u are logged in: docker login
1. To build the docker Image, this command is used --> docker build -t mlops-docker-demo
2. This command is used to run the existing docker image in any terminal --> docker run -p 5000:5000 mlops-docker-demo
3. Tag your image docker tag mlops-docker-demo razz32/mlops-docker-demo:latest
4. Push the image to dockerhub--> docker push razz32/mlops-docker-demo:latest
5. Pull the image to dockerhub: docker pull razz32/mlops-docker-demo:latest
6. Run the pulled Image: docker run -p 5000:5000 razz32/mlops-docker-demo:latest