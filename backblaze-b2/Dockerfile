FROM python:3.9-alpine

# https://pypi.org/project/b2/
ENV BACKBLAZE_B2_VERSION 2.1.0

RUN set -eux; \
	pip install --no-cache-dir "b2 == $BACKBLAZE_B2_VERSION"

CMD ["b2", "--help"]
