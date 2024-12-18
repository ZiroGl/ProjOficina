# Documentação do Sistema Oficina

## Visão Geral
Este projeto é um sistema para gestão de oficinas, contendo funcionalidades para cadastro e gerenciamento de clientes, produtos, usuários, veículos, serviços e estoque. Inclui um sistema de login e logout, além de interações com um banco de dados relacional para armazenar as informações necessárias. Segue credenciais padrões para logar no sistema, Usuário: admin; senha: admin

## Estrutura do Projeto

### Diretório Raiz
- **index.php**: Página principal do sistema.

- **login.php**: Página de autenticação de usuários.
- **bdoficina.sql**: Script do banco de dados.

### Diretório `cadastro`
Arquivos dedicados ao cadastro de entidades no sistema:
- **cadClientes.php**: Cadastro de clientes.
- **cadProduto.php**: Cadastro de produtos.
- **cadUsuario.php**: Cadastro de usuários.
- **cadVeiculo.php**: Cadastro de veículos.
- **cadServico.php**: Cadastro de serviços.
- **cadEstoque.php**: Cadastro de estoque.

## Banco de Dados
O banco de dados é configurado através do script **bdoficina.sql**, que define tabelas e relações para:
- Usuários
- Clientes
- Produtos
- Veículos
- Serviços
- Estoque

## Principais Funcionalidades
1. **Autenticação**:
   - Implementada nos arquivos `login.php` e `logout.php`.
   - Gerencia acesso ao sistema com segurança.

2. **Cadastro e Gerenciamento**:
   - Módulos para adicionar, visualizar e modificar dados de clientes, produtos, usuários, veículos, serviços e estoque.


## Configuração
1. **Banco de Dados**:
   - Importe o arquivo `bdoficina.sql` em um servidor MySQL.

2. **Servidor Web**:
   - Certifique-se de que o PHP e o MySQL estão configurados corretamente.
   - Coloque os arquivos do projeto em um diretório acessível pelo servidor web.

3. **Login Inicial**:
   - Acesse `login.php` para autenticar-se.

## Relação de desenvolvimento
- Bernaro Z. : Interface, Crud de Usuários e Veículos e estilização.
- Gabriel Lucas G. : Criação do banco de dados e Crud de Produtoes e Estoque.
- Henrique Fantinel : Criação do Crud de Clientes e Serviços.

<h3>LAYOUTS DAS PÁGINAS</h3>
<h1>Tela de login</h1>
<img src="https://github.com/user-attachments/assets/3440c79f-d410-4a2c-9ba7-deef984feab1" width="500" height="260">

<h1>Tela home</h1>
<img src="https://github.com/user-attachments/assets/500300e2-8c0e-48d6-9401-da381000510f" width="500" height="260">

<h1>Tela produtos</h1>
<img src="https://github.com/user-attachments/assets/232f8e65-aa64-4b62-86f3-f9883ab3af4e" width="500" height="260">

<h1>Tela cadastro de produtos</h1>
<img src="https://github.com/user-attachments/assets/b7446e44-101f-451c-9c01-bdeca48d08b6" width="500" height="260">

<h1>Tela editar produto </h1>
<img src="https://github.com/user-attachments/assets/130ba6ba-35c1-47da-950c-4f9eff1241eb" width="500" height="260">

<h1>Tela veículos</h1>
<img src="https://github.com/user-attachments/assets/f25fd193-3b9d-4c76-bac5-5b8facc6dfab" width="500" height="260">

<h1>Tela cadastrar veículo</h1>
<img src="https://github.com/user-attachments/assets/eb239a96-77cd-447d-82db-a5a2ff3f46f7" width="500" height="260">

<h1>Tela editar veículo<h1>
<img src="https://github.com/user-attachments/assets/9c609afe-c040-4bb1-893c-06a0149189b8" width="500" height="260">

<h1>Tela clientes<h1>
<img src="https://github.com/user-attachments/assets/81eba2e2-a654-4128-b62e-3c18366a1bf6" width="500" height="260">

<h1>Tela cadastrar clientes<h1>
<img src="https://github.com/user-attachments/assets/b2eed3c0-5958-4ffa-9659-3d38d92fcd0c" width="500" height="260">

<h1>Tela editar cliente<h1>
<img src="https://github.com/user-attachments/assets/5fe27a70-8248-48cd-8b2b-8c560182a19d" width="500" height="260">

<h1>Tela serviço<h1>
<img src="https://github.com/user-attachments/assets/ab40afde-f06e-4610-b111-2a38a3ccdff7" width="500" height="260">

<h1>Tela serviço<h1>
<img src="https://github.com/user-attachments/assets/ab40afde-f06e-4610-b111-2a38a3ccdff7" width="500" height="260">




