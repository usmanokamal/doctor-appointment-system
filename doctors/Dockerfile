# Use the official Python image as the base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the Python file into the container
COPY . .

RUN pip install flask

# Expose the port the Flask app runs on
EXPOSE 9090

# Define the command to run the Flask application
CMD ["python", "app.py"]

