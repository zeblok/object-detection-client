FROM openvino/model_server:2022.1
USER root
RUN  mkdir -p /models/person-vehicle-bike-detection-2002/
COPY "./person-vehicle-bike-detection-2002.bin" "./person-vehicle-bike-detection-2002.xml" /models/person-vehicle-bike-detection-2002/1/
COPY ./config.json /models/
RUN  chown -R ovms:ovms /models/
USER ovms