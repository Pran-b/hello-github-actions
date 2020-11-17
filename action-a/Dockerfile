FROM ubuntu
RUN apt-get update -y
RUN apt-get install -y python3-pip
RUN apt-get install -y python-dev
RUN python3 -m pip install pip --upgrade --force-reinstall
ADD testentry.py /testentry.py
RUN chmod +x /testentry.py
ENTRYPOINT ["python3", "/testentry.py"]
