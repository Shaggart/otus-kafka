# Домашнее задание - Чтение данных из Kafka

## Задача

Написать приложение на Scala, которое будет выполнять следующее:
- Вычитывать из CSV-файла, который можно скачать по ссылке - https://www.kaggle.com/sootersaalu/amazon-top-50-bestselling-books-2009-2019, данные, сериализовывать их в JSON, и записывать в топик books локльно развернутого сервиса Apache Kafka.
- Вычитать из топика books данные и распечатать в stdout последние 5 записей (c максимальным значением offset) из каждой партиции. При чтении топика одновременно можно хранить в памяти только 15 записей.
