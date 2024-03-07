# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
ARG BUILD_FROM
FROM $BUILD_FROM

RUN pip install pyyaml && pip install PyModbus && pip install paho-mqtt

# Copy root filesystem
COPY rootfs /

