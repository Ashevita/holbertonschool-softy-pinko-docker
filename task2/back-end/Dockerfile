FROM python:3.8
WORKDIR /app
RUN apt-get update -y && apt-get install -y python3 python3-pip
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED
RUN pip3 install flask
COPY . /app
EXPOSE 5252
CMD ["python3", "/app/api.py"]
