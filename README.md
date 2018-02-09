# neo4j-apoc
Dockerfile for Neo4j with installed APOC Plugin

It has the same Options as the o [fficial Neo4j-Image](https://hub.docker.com/_/neo4j/)

Make sure that you allow apoc to run its procedures like this:
 
 ```
  docker run umbag/neo4j -e NEO4J_dbms_security_procedures_unrestricted=apoc.*
 ```
 
 