# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Docker

Pra rodar o docker file execute dentro da pasta `src`

Primeiro faz o build da imagem

```bash
docker build -t conversao_temperatura .
```

E depois roda com 

```bash
docker container run -d -p 8080:8080 conversao_temperatura
```

Ele estara rodando na porta 8080
