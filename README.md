# CRUD PYTHON EM MYSQL
🎈GERENCIE O NOME E IDADE DOS USUÁRIOS NA DATABASE MYSQL.

<img src="./IMAGENS/FOTO_1.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Este aplicativo é um gerenciador de usuários que permite adicionar, listar, atualizar e excluir informações de usuários armazenadas em um banco de dados MySQL CRUD. Ele foi projetado para fornecer uma interface simples e interativa para manipular os dados dos usuários.

Funcionalidades principais:

1. **Adicionar Usuário**: Permite adicionar um novo usuário ao banco de dados, fornecendo o nome e a idade do mesmo.

2. **Listar Usuários**: Apresenta uma lista de todos os usuários cadastrados no banco de dados, mostrando seus nomes e idades.

3. **Atualizar Usuário**: Permite atualizar as informações de um usuário existente no banco de dados, substituindo o nome e/ou a idade pelo novo valor fornecido.

4. **Excluir Usuário**: Remove um usuário específico do banco de dados com base no nome fornecido.

O aplicativo fornece um menu intuitivo para o usuário interagir com essas funcionalidades. Ele utiliza a linguagem de programação Python e o conector MySQL para estabelecer a conexão com o banco de dados e executar as operações de manipulação de dados.

Essa aplicação é útil em cenários onde é necessário armazenar e gerenciar informações de usuários de forma eficiente, como em sistemas de cadastro, administração de usuários em plataformas web, entre outros.

## EXECUTANDO O PROJETO:
### 1. IMPORTAÇÃO DO BANCO DE DADOS:
   - Antes de executar o aplicativo, importe o arquivo `DATABASE.sql` fornecido para o seu banco de dados MySQL. 

### 2. CONFIGURANDO A CONEXÃO COM O MYSQL:
    - Certifique-se de substituir `localhost`, `seu_usuario`, e `sua_senha` pelos valores corretos no arquivo `./CODIGO/.env`. O arquivo `.env` deve conter as seguintes variáveis de ambiente:
   ```env
   DB_HOST=localhost
   DB_NAME=cadastro
   DB_USER=seu_usuario
   DB_PASSWORD=sua_senha
   ```

### 3. INTALANDO AS DEPEDÊNCIAS:
   - Entre no diretório `CODIGO` e execute o comando:

   ```bash
   pip install -r requirements.txt
   ```

### 4. EXECUTANDO O APLICATIVO:
   - Para executar o arquivo Python, utilize o comando abaixo no terminal, dentro do diretório `./CODIGO`:

   ```
   python CODIGO.py
   ```

   - Isso iniciará o aplicativo Python que permite adicionar, listar, atualizar e excluir usuários do banco de dados `cadastro`.

### 5. INTERAGINDO COM APLICATIVO:
1. **Adicionando um Usuário**:
   - Selecione a opção `1`.
   - Digite o nome do usuário e pressione Enter.
   - Digite a idade do usuário e pressione Enter.

2. **Listando Usuários**:
   - Selecione a opção `2`.
   - O programa exibirá a lista de usuários cadastrados.

3. **Atualizando um Usuário**:
   - Selecione a opção `3`.
   - Digite o nome do usuário a ser atualizado e pressione Enter.
   - Digite o novo nome do usuário e pressione Enter.
   - Digite a nova idade do usuário e pressione Enter.

4. **Excluindo um Usuário**:
   - Selecione a opção `4`.
   - Digite o nome do usuário a ser excluído e pressione Enter.

5. **Saindo do Programa**:
   - Selecione a opção `5`.
   - O programa exibirá uma mensagem de saída e encerrará a execução.

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CURSO DE MYSQL](https://github.com/VILHALVA/CURSO-DE-MYSQL)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)


