# Use an official Python runtime as the parent image
FROM python:3.6
# Set the working directory in the container to /app
WORKDIR /app
# Copy the current directory contents into the container at /app
ADD . /app
# Make the container's port 80 available to the outside world
EXPOSE 5000
#Install flask
RUN pip install -r requirements.txt
# Define ENTRYPOINT
ENTRYPOINT ["python"]
# Run app.py when the container launches
CMD ["app.py"]
