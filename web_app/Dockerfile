FROM ubuntu:latest

WORKDIR /home/ubuntu
COPY ./app.py /home/ubuntu/.

RUN apt update && apt install -y \
    python3 \
    python3-pip
RUN pip3 install web.py

CMD python3 app.py

