FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y ansible git && \
    apt-get clean

COPY . /ansible

WORKDIR /ansible

CMD ["ansible-playbook", "playbook.yml"]
