# Use the official Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . .

# Install Bottle
RUN pip install --no-cache-dir bottle

# Expose port 8080 to the outside world
EXPOSE 8080

# Define environment variable
ENV NAME World

# Command to run the Bottle application
CMD ["python", "examples/simple_app.py"]
