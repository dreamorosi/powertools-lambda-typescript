# version 9.5.35
FROM squidfunk/mkdocs-material@sha256:09b9cb8cc0a813f1b96460b28fcf4bc1e1a18e4318256a7e19e259a8f0cb0092

COPY requirements.txt /tmp/
RUN pip install --require-hashes -r /tmp/requirements.txt
