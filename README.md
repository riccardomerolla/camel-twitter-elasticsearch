camel-twitter-elasticsearch
===========================

Storing tweets in Elasticsearch with Camel

Start camel route with: 

- mvn camel:run 

and watch tweets stored in Elasticsearch

- curl -XGET 'http://localhost:9200/twitter/tweet/_count'