## Terminal Access
docker exec -it neo4j_neo4j_1 bash
# in the container:
cypher-shell -u neo4j -p password

## Browser Access
http://localhost:7888/browser/

## query example:
MATCH (n) RETURN count (n);