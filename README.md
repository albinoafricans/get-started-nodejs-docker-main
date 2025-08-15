
<h3 align="center">
  Projeto para estudo do docker com o nodeJs
</h3>

<p align="center">
  Nesse projeto tem os arquivos do docker e do docker-compose totalmente documentados para facilitar o seu estudo com esplicações dos comandos.
</p>

## Como usar ?

- Buildar os containers
```
 docker-compose up --build -d
```

- Iniciar os containers
```
 docker-compose up -d
```

- Derrubar os containers
```
 docker-compose down
```

- Após iniciar os containers basta acessar o endpoint http://localhost:3333/ para receber o seu oi do Albino :smile:.


- Necessário alterar as configuraçoes de Conexão do MySQL para se conectar via DBeaber - Setar propriedade allowPublicKeyRetrieval para TRUE


