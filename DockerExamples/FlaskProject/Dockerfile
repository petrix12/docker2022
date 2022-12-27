FROM python:3.8-buster
RUN pip install flask==2.2.2
COPY code/ /var/opt/

WORKDIR /var/opt
CMD python app.py