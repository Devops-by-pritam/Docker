From ubuntu:latest

#set the working directory in the image
WORKDIR /app

#copy the files from host system to the image file system
COPY . /app

#insrall the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

#set the enviroment variables
ENV NAME World
#Run a command to start the application
CMD ["python3", "app.py"]

