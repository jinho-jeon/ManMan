FROM tensorflow/serving:1.13.0-devel
RUN mkdir -p /app/manman
COPY manman_input_data.py /app
COPY manman_client_rest_rpc.py /app
COPY manman /app/manman
RUN chmod 777 -R /app
WORKDIR /app
