# Bootcamp #001 Qualiters Club

Teste de API Rest do manual ao CI/CD

## O que é
Este repositório foi criado para o bootcamp de testes de API Rest.

## Tecnologias utilizadas
- Postman versão web
- node v20.10.0
- newman v6.2.1
- newman-reporter-html


## Documentações
- Doc da API [Consulte Swagger](https://serverest.dev/#/)
  
# Como instalar o ambiente
- Primeiro: instale o node no seu computador [Baixe aqui] (https://nodejs.org/en/download)
- Segundo: realize a instalação do newmam de forma global [Baixe aqui a dependencia](https://www.npmjs.com/package/newman)

```
npm install -g newman
 ````
- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reporter-htmlextra] (https://www.npmjs.com/package/newman-reporter-htmlextra)
```
npm install -g newman-reporter-htmlextra
```


## Como rodar os testes

### Pelo Postman web ou desktop
- Importe a collection e o environment.
- Execute os testes de forma manual ou automatizada
### Pelo newman
- Abra seu console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run serveRest.postman_collection.json -e serveRest.postman_environment.json -r cli
```
- Execute os testes com relatório
```
newman run serveRest.postman_collection.json -e serveRest.postman_environment.json -r cli,htmlextra
```
### Report
Se você optou por os testes com o report htmlextra, você gerou um arquivo html 
com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que 
foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato
email: fabricio_luis@outlook.com

redes sociais: https://linktr.ee/fabricioperrone
