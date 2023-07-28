# Dockerfile for service2
FROM python:latest

# Set the working directory
WORKDIR /app

# Copy the rest of the application files
COPY . .

# Install pytest and other Python dependencies
RUN pip install pytest

# Your other Dockerfile commands go here...

# Start the application
CMD ["python", "manage.py", "runserver"]
