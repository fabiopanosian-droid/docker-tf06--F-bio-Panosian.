# docker-tf06-Fábio Panosian

## Estrutura
- docker-compose.yml
- nginx/Dockerfile
- nginx/index.html

## Comandos executados

### docker-compose up -d
```bash
cd /home/fabio/lab_compose_tf06
docker-compose up -d --build
```

### docker-compose ps
```bash
docker-compose ps
```

### Teste de conectividade (ping via DNS interno)
```bash
docker exec -it $(docker-compose ps -q web) sh -c "ping -c 2 cache"
```

## Observações
Este repositório deve ser enviado como público no GitHub com nome `docker-tf06-[NOME-DO-ALUNO]`.
