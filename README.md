elasticsearch-php-test
======================

Elasticsearch php test

<<<<<<< HEAD
Install elastic search using the following commands:

wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-0.90.7.deb
dpkg -i elasticsearch-0.90.7.deb

You can also install it using a repository for debian based distributions the following way:

wget -O - http://packages.elasticsearch.org/GPG-KEY-elasticsearch | apt-key add -
deb http://packages.elasticsearch.org/elasticsearch/0.90/debian stable main

Run apt-get update and the repository is ready for use.
Finally install with the following command: apt-get install elasticsearch


Test if server is up and running (May take a while to run the first time)

curl -X GET 'http://localhost:9200'



https://www.digitalocean.com/community/articles/how-to-install-elasticsearch-on-an-ubuntu-vps

http://www.elasticsearch.org/guide/en/elasticsearch/client/php-api/current/_quickstart.html
