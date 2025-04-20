# Use official Python image
FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy all files into the container
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port (adjust as needed)
EXPOSE 8000

# Run the application (adjust if using Flask, FastAPI, etc.)
CMD ["python", "app.py"]
