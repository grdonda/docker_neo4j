# Neo4J

## Docker build

acessar a pasta docker e rodar o comando para criar a instancia

```
docker-compose -f "./docker-compose.yml" up -d --build
```

```
docker-compose -f "./docker-compose.yml" down --remove-orphans
```

## Docker - listagem de instancias

```
docker ps -a
```

## Docker - acessando o shell

```
docker exec -it {instance name} sh
```

## Docker - start neo4j

[start|restart|stop]

```
docker start neo4j
```

## Docker - logs neo4j

```
docker logs neo4j
```

&nbsp;
&nbsp;

## Configurações

Preconfigurei um usuario(root) e senha(root) e também um banco de dados (db)

- username: neo4j
- password: root
- database: 

&nbsp;
&nbsp;

# IDE

Para acessar o mongo DB utilizo o DBeaver que tem suporte ao banco de dados.

Ref.:  


&nbsp;
&nbsp;

## Neo4j CRUD Operations
https://neo4j.com/docs/  

### SQL Cypher
https://neo4j.com/docs/cypher-manual/current/

