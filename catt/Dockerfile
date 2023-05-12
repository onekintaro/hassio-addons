FROM homeassistant/{arch}-base-python:3.9-alpine

# Install dependencies
RUN apk add --no-cache --virtual .build-deps \
    gcc \
    jpeg-dev \
    openjpeg-dev \
    musl-dev \
    libffi-dev \
    openssl-dev \
    && pip3 install catt \
    && apk del .build-deps

# Copy CATT config file to container
COPY config.json /share/catt/config.json

# Start CATT
CMD ["catt", "serve", "-f", "/share/catt/config.json"]