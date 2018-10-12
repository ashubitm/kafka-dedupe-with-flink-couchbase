# kafka-dedupe-with-flink-couchbase
streaming kafka flink duke-dedupe and couchbase
read from kafka streaming JSON streams for 3 seconds .
Assuming 1 record will come but can be more call the dedeupe engine from flink which will check the existing index and add to it.
Then finally save the record to couchbase.
Some of the processing are commented that needs to be uncommented based on properties file (Kakfa-topics,couchbase settings )
