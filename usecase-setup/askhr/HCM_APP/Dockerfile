# Specify the base image (Python 3.11)
FROM python:3.11

# Install pip3
RUN apt-get update && apt-get install -y --no-install-recommends python3-pip
# RUN pip3 --version

COPY . /src
WORKDIR /src
RUN chmod -R 777 /src

RUN pip3 install -r requirements.txt 

#Expose ports for Fast API backend 
EXPOSE 8000  

#Deploy the server
CMD ["uvicorn", "prof_mgmt:app", "--host", "0.0.0.0", "--port", "8000"]
