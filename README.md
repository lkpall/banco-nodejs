# Requisitos para rodar o código
  - Instalar o Node e o Yarn
* A partir daqui é recomendável que se utilize uma virtualenv

* Com a venv instalada e ativada execute o comando "yarn init -y" para criar um 
package.json com configurações e dependências do projeto

* Execute o comando "yarn add express" instala mais algumas depências do projeto

* Para executar o projeto basta digitar o comando "node src/index.js"

* Outra opção para iniciar o projeto é instalar outra depência que é o nodemon com
o comando "yarn add nodemon -D", para assim que houver alguma alteração no pro-
jeto ele já desce e sobe o localhost automaticamente com as alterações


# Nesse projeto é efetuado um sistema de cadastro de conta bancária
# nele é implementado as seguintes funcionalidades e regras:
- Cadastro de conta
- Validação de CPF existente
- Listar extrato
- Validação de conta
- Implementação de Middlewares para as validações
- Depósito de conta
- Saque
- Listar extrato por data
- Atualizar informações da conta
- Deletar conta 

# Para fazer os testes do projeto com os metódos POST, PUT, PATCH E DELETE. Foi utilizado o Insomnia.