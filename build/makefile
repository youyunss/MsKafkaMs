all:consumer producer
.PHONY:all
consumer:
	g++ -o ../bin/consumer ../src/consumer/kafkaconsumer.cpp -I../lib -I/usr/local/include/librdkafka/ -L/usr/local/include/ -lrdkafka -lrdkafka++ --std=c++11
producer:
	g++ -o ../bin/producer ../src/producer/kafkaproducer.cpp -I../lib -I/usr/local/include/librdkafka/ -L/usr/local/include/ -lrdkafka -lrdkafka++ --std=c++11
