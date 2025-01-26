FROM ubuntu:latest

# Set the working directory in the image
WORKDIR /app

# Copy the files from the host file system to the image file system
COPY . /app

# Install the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip
RUN pip3 install flask
ENTRYPOINT FLASK_APP=./app.py flask run --host=0.0.0.0 --port=8080
