FROM python:3.12-slim

# Copy requirements.txt to the container
COPY requirements.txt /requirements.txt

# Install required Python packages
RUN pip install --no-cache-dir -r /requirements.txt

# Copy deployment.py to the container
COPY deployment.py /deployment.py

# Set the default command to run deployment.py
CMD ["python", "/deployment.py"]
