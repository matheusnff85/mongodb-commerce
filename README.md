# MongoDB Commerce

Neste projeto o objetivo era trabalhar com o banco de dados mongo, contendo dados do cardápio do McDonald's como ingredientes, valores nutricionais, e dados fictícios de vendas, por meio de desafios os comandos para o banco de dados foram desenvolvidos cada um em seu respectivo arquivo de nome `desafioN.js` sendo N números de 1 a 32 os mesmos estão localizados na pasta `./challenges`.

### Tecnologias utilizadas

MongoDB e Docker.

### Como utilizar a aplicação

**É necessário ter o docker instalado em sua máquina para utiliza-lo**

- ##### Siga os passos abaixo

- 1 - Clone o repositório com o comando `git clone` e a chave ssh do repositório.

- 2 - Acesse a raiz do projeto e utilize o comando `docker run -d --name=nomeDoContainer-v "$PWD:/app" -p 27017:27017 mongo:5.0`

- 3 - Após garantir que o container está em execução utilize o comando `docker exec -it nomeDoContainer mongosh` sendo o paramêtro "nomeDoContainer" o nome escolhido por você no processo 2.

- 4 - Copie todo o código contido no arquivo `./db.mongodb` na raiz do projeto, cole o que foi copiado no terminal aberto no processo 3 e pressione ENTER.

---

- Desenvolvido por [Matheus Marinho](https://www.linkedin.com/in/matheus-marinhodsp/).
