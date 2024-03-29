# PI - Sistema de PDV (Ponto de Venda)

## Descrição
O PI (Projeto de Integração) é um sistema de PDV utilizado para o cadastro de clientes, produtos e vendas. Ele funciona com uma conexão SQL para o banco de dados, sendo essencial para seu funcionamento. O sistema utiliza Java Spring e JavaScript para a interface de usuário.

## Funcionalidades
- Cadastro de clientes
- Cadastro de produtos
- Registro de vendas
- Sistema de login com diferentes níveis de acesso
  - Gerente: acesso a todas as telas
  - Atendente: acesso a todas as telas exceto as relacionadas às vendas
  - Vendedor: acesso a todas as telas exceto as relacionadas aos produtos

## Tecnologias Utilizadas
- Java Spring
- JavaScript
- Banco de dados SQL

## Instalação e Uso
1. Clone o repositório:
   
   git clone https://github.com/F4bi0zin/PI.git
   
3. Configure o banco de dados SQL de acordo com as necessidades do projeto.
4. Instale as dependências do projeto.
5. Execute o sistema:
   
   mvn spring-boot:run
   
## Criador
Fabio Miguel
