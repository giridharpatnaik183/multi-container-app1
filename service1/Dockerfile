# Use a base image suitable for your application (e.g., Python, Node.js, etc.)
FROM python:3.9

# Set the working directory inside the container
WORKDIR /app

# Copy the application code into the container
COPY . /app

# Install dependencies (if any)
RUN pip install --no-cache-dir -r requirements.txt

# Specify the command to run your application
CMD ["python", "app.py"]

