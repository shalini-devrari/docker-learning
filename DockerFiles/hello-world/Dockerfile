#Use the official Ubuntu image as a base
FROM ubuntu:20.04

#Set the working directory in the container
WORKDIR /app

#Copy the script file from the host to the container
COPY hello-world.sh /app/

#Make the script executable 
RUN chmod +x /app/hello-world.sh

#Command to run the script
CMD ["/app/hello-world.sh"]
