FROM ubuntu:latest

#set working directory in the image
WORKDIR ./app
#copy file from host to image
COPY . /app 

#install dependencies
RUN apt-get update && apt-get install -y pyton3 python3-pip

#set env
ENV NAME World

#run the app
CMD ["python3", "app.py"] 
