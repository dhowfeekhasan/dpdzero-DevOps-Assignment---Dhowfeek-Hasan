# Use Python base image
FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Copy files to container
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port used in app.py (e.g., 8002)
EXPOSE 8002

# Start the app
CMD ["python", "app.py"]
