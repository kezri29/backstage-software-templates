#python image pulling from docker images
FROM python:3.10-alpine

# copying the requirements file to the container in tmp folder
COPY requirements.txt /tmp

# installation of the requirements in the container
RUN pip install -r /tmp/requirements.txt

# setting the working directory in the container 
COPY ./src /src

# running the application
CMD python /src/app.py


