# Use the official Python image
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy the application files
COPY app.py /app/

# Install Flask
RUN pip install flask

# Expose port 5000
EXPOSE 5000

# Start the Flask app
CMD ["python", "app.py"]

