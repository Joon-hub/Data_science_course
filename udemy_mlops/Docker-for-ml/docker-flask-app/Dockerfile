FROM python:3.8

# set a directory for the app
WORKDIR /usr/src/app

# copy all the files to the container
COPY . . 

# install all the dependencies from requirements.txt 
RUN pip install --no-cache-dir -r requirements.txt 

# tell the port number container should expose
EXPOSE 8080

# run the command
CMD ["python", "./app.py"]