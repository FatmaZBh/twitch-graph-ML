Prerequisites : Docker installed on your computer

Setup instructions : 

1- Before running this notebook, you need to first run this Docker command in your terminal : 


docker run \
  --name neo4j-gds \
  -p 7474:7474 \
  -p 7687:7687 \
  -d \
  --env NEO4J_AUTH=neo4j/password \
  --env NEO4J_PLUGINS='["graph-data-science"]' \
  neo4j:latest




2- Wait for neo4j to fully start (this step can take some time  1 to 2 minutes 

3- Once neo4j is started, you can run the notebook cells. 
