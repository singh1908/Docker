# Use an official Python runtime as a base image
FROM python:3.11-slim

# Set the working directory in the container
WORKDIR /app

# Copy only the Python script into the container
COPY app.py .

# Run the Python script when the container starts
CMD ["python", "app.py"]
