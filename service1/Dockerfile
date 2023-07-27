# Use a base image suitable for your application (e.g., Python, Nginx, etc.)
FROM python:3.9

# Set the working directory inside the container
WORKDIR /app

# Copy the requirements.txt file into the container (assuming it is in the same directory as the Dockerfile)
COPY requirements.txt /app/

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code into the container
COPY . /app/

# Specify the command to run the web server
CMD ["python", "app.py"]
