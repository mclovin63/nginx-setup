# Базовый образ
FROM bitnami/kafka:latest

#переменные среды
ENV KAFKA_CFG_ZOOKEEPER_CONNECT=zookeeper:2181
ENV ALLOW_PLAINTEXT_LISTENER=yes

#открываем порты для Kafka
EXPOSE 9092

# Запускаем Kafka при старте контейнера
CMD ["/opt/bitnami/scripts/kafka/run.sh"]
