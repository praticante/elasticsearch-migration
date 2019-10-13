# elasticsearch-migration

docker-compose run elasticdump sh

elasticdump \
  --input=http://elasticsearch543:9200/logstash-randomlog-1 \
  --output=http://elasticsearch740:9200/logstash-randomlog-1 \
  --type=mapping
  
elasticdump \
  --input=http://elasticsearch543:9200/logstash-randomlog-1 \
  --output=http://elasticsearch740:9200/logstash-randomlog-1 \
  --type=data
  

elasticdump \
  --input=http://elasticsearch543:9200/logstash-randomlog-1 \
  --output=logstash-randomlog-1.json \
  --type=data
