# SempreLeio



O sempreLeio é uma plataforma web que possibilita o encontro para leitores e profissionais do ramo de livros.

## Início

Estas instruções permitem que você obtenha uma cópia do projeto e configure
em seu computador para desenvolvimento e testes.


### Executar em modo desenvolvimento

#### Banco de dados local

O projeto está configurado para acessar uma base de dados PostreSQL. Você pode
configurar um banco de dados em seu computador. Para isso crie um banco de dados `pgdb`, cujo dono é o usuário chamado
`pguser` com permissões de criação de tabelas e senha `pgpasswd`.

#### Imagem docker do PostgreSQL

Você pode usar uma imagem `docker` do PostreSQL como servidor local do Banco
de dados. Para iniciar uma imagem já configurada para o banco execute o _script_
local `docker_run_postgres.sh`.

```sh
./docker_run_postgres.sh
```

#### Executar

Para executar em modo de desenvolvimento, com o banco de dados funcionando,
no diretório do projeto, digite

```sh
sbt run
```

## Documentação

Verifique o diretório [`doc`](./doc/) para a documentação do sistema

## Contribuindo

Veja o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para maiores detalhes.

## Equipe de desenvolvimento

* **André Luiz do Nascimento** - *email@dominio.com*
* **Ricardo Carvalho** - *email@dominio.com*

## Licença

Este projeto é licenciado pela GNU [GPL 3](LICENSE.md).
