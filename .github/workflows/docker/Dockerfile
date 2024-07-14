FROM python:3.8-slim

# Install dependencies
RUN pip install flask

# Copy application code
COPY app /app

# Set the working directory
WORKDIR /app

# Run the application
CMD ["python", "app.py"]
