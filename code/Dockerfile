FROM python:alpine

ADD app.py .
RUN apt install python-pip
RUN pip install pymongo
CMD ["python3","./app.py"]
