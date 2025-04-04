# Use official Python image
FROM python:3.9

# Set working directory
WORKDIR /app

# Copy dependencies
COPY requirements.txt .

# Install dependencies
RUN pip install -r requirements.txt

# Copy application files
COPY . .

# Expose port
EXPOSE 5000

# Run application
CMD ["python", "app.py"]

