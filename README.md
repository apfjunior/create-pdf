## :memo: Sobre o Projeto
Baseia-se em um protótipo genérico para um formulário do técnico de campo de TI da empresa SONDA/CTIS. Pois quando surge alguma ordem de serviço fora do sistema padrão da empresa, o técnico deverá imprimir uma OS em branco e preencher manualmente. Desta forma, muitas das vezes, algumas informacões não eram compreensíveis no ato da leitura pelo setor responsável. 

Dito isso, este projeto ao receber as informações fornecidas no formulário, gerará um arquivo PDF para impressão. Sua estrutura pode ser usada em outros projetos **livremente**.

<p align="center">
  <img alt="covid19-tracker" src="client/src/assets/new-exemple.gif" width="60%">
</p>


## :hammer_and_wrench: Build
- [Axios](https://github.com/axios/axios)
- [Express](https://expressjs.com/)
- [Cors](https://github.com/expressjs/cors)
- [React](https://reactjs.org/)
- [Html-pdf](https://www.npmjs.com/package/html-pdf)
- [Body-parser](https://www.npmjs.com/package/body-parser)
- [Nodemon](https://www.npmjs.com/package/nodemon)

## :information_source: How To Use
```bash
# Clone esse repositório
$ git clone https://github.com/apfjunior/create-pdf.git

# Entre no projeto
$ cd create-pdf

# Instale as dependências do "client" e "server" projeto. Desta forma:
# Client
$ cd client && npm i

# Server
$ cd server && npm i

# Serão necessários 02 terminais simultâneos para execucão. Um para o "client" 
$ cd client && npm start

# Outro para o "server"
$ cd server && npm start
```

-----
:wave: [Let's Connect!](https://www.linkedin.com/in/antoninopraxedes/)


