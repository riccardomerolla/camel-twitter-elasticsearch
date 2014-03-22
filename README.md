camel-twitter-elasticsearch
===========================

Storing tweets in Elasticsearch with Camel

Start camel route with: 

- mvn camel:run 

and watch tweets stored in Elasticsearch (the cluster has to be named elasticsearch or use docker container above)

- curl -XGET 'http://localhost:9200/twitter/tweet/_count'

If you need Elasticsearch instance try to use Docker ;-)

1. Install Docker
2. Download trusted build from public Docker Registry: 
-- docker pull dockerfile/elasticsearch
3. Run Elasticsearch
-- docker run -d -p 9200:9200 -p 9300:9300 dockerfile/elasticsearch