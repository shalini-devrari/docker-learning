#Use the official Ubuntu image as a base
FROM ubuntu:20.04

#Install Python
RUN apt-get update && apt-get install -y python3

#Set the working directory in the container
WORKDIR /app

#Copy the current directory contents into the container at /app
COPY . /app/

#Run the Python Script
CMD ["python3", "app.py"]