FROM python:3.8
MAINTAINER Roman Kojnok <roman.kojnok@protonmail.com>

WORKDIR /app
RUN apt-get update && apt-get install -y python3-pip

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY app.py .

# Set YOUR_NAME environment variable
ENV YOUR_NAME=m0rph3us
# Expose the correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["/usr/local/bin/python3", "app.py"]
