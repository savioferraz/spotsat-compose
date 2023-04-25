# Spotsat Docker-Compose

Docker-compose da aplicação SpotSat

## Instalação

Para instalar esse Docker-compose, clone esse repositório e rode os seguintes comandos:

```sh
git submodule init
git submodule update
```

Certifique-se de que os diretórios do front e back end estão no mesmo diretório do compose.
Execute o comandos para gerar as imagens dos containers:

```sh
docker compose build
```

## Uso

Para usar a aplicação em containers, execute o comando:

```sh
docker compose up
```

A aplicação ficará disponível na porta:

```sh
http://localhost:8080/
```
