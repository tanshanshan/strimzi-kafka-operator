FROM strimzi/kafka-base:latest

# copy scripts for starting Mirror Maker
COPY ./scripts/ $KAFKA_HOME

USER 1001

CMD ["/opt/kafka/kafka_mirror_maker_run.sh"]
