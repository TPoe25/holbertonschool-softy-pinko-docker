# getting latest unbuntu version
FROM python:latest

# Install packages using pip3
RUN pip3 install flask
RUN pip3 install flask-cors

# Set working directory
WORKDIR /app

# Copy Python file to container
COPY ./api.py /app/api.py

# Define command to run the package
CMD [ "python3", "api.py" ]