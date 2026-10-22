FROM python:3

WORKDIR /opt/node
RUN pip install --no-cache-dir --upgrade "pip>=26.2.2" \
    && pip install codespell
WORKDIR /vm
ENTRYPOINT ["codespell"]
