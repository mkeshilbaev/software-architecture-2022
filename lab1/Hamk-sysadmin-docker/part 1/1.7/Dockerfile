FROM ubuntu

COPY script.sh .

RUN apt-get update \
    && apt-get install -y curl  

RUN chmod +x script.sh

CMD ["./script.sh", "helsinki.fi" ]