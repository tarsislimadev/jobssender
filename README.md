# Jobs sender

Encontra vagas de programação (atraves de webscraping)

## O projeto

Entra em sites e listas de vagas, procura por palavras-chave e envia propostas (curriculo e/ou portfolio) para empregadores.

Encontra nos links:

- [ ] GitHub
- [ ] APInfo
- [ ] Linkedin

Envia propostas a partir das caixas de e-mail:

- [ ] Gmail
- [ ] Hotmail/Outlook
- [ ] Yahoo Mail

## Como usar o projeto (off-line)

Instalar [Docker (+ docker compose)](https://www.docker.com/)

Executar:

```sh
bash ./env/development/up.sh 
```

Acessar `http://localhost`

## Como usar o projeto (Docker)

Instalar [Docker](https://www.docker.com/)

Executar:

```sh
docker run --rm -p 80:80 tmvdl/jobs-search
```

## License

[MIT](./LICENSE)
