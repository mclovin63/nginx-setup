# Базовый образ
FROM bitnami/kafka:latest

# Устанавливаем переменные среды
ENV KAFKA_CFG_ZOOKEEPER_CONNECT=zookeeper:2181
ENV ALLOW_PLAINTEXT_LISTENER=yes

# Открываем порты Kafka
EXPOSE 9092

# Запуск Kafka при старте контейнера
CMD ["/opt/bitnami/scripts/kafka/run.sh"]
