see: 

# Run Neo4j Server

For ARM computers
```shell
docker run \
  --publish=7474:7474 \ 
  --publish=7687:7687 \
   --volume=$HOME/neo4j/data:/data \
    arm64v8/neo4j:2025-community-bullseye
```

# Run Application