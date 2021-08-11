FROM python:3.6
LABEL maintainer 'Alan Ensina'

RUN useradd alanensina && \
    mkdir /app && \
    mkdir /log && \
    chown alanensina /log

USER alanensina
VOLUME /log
WORKDIR /app
EXPOSE 8000

ENTRYPOINT ["/usr/local/bin/python"]
CMD ["run.py"]