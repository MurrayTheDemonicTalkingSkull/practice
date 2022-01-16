FROM rabbitmq:3.6-management


RUN rabbitmq-plugins enable --offline rabbitmq_mqtt rabbitmq_federation_management rabbitmq_stomp
COPY rabbitmq.config /etc/rabbitmq/rabbitmq.config
RUN chmod 777 /etc/rabbitmq/rabbitmq.config
EXPOSE 5672
EXPOSE 15672
