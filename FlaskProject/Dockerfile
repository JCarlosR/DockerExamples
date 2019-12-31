FROM python:3.8-buster
RUN pip install flask==1.1.1
COPY code/ /var/opt/

WORKDIR /var/opt
CMD python app.py
