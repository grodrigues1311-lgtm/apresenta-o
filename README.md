Projeto Web - Cadastro de Amigos

Sistema web desenvolvido em PHP com funcionalidades de Login, Controle de Acesso e CRUD (Create, Read, Update, Delete) para gerenciamento de amigos.

📋 Sobre o Projeto

Este projeto tem como objetivo demonstrar a criação de uma aplicação web integrada com banco de dados, permitindo o cadastro e gerenciamento de amigos através das operações CRUD, além de um sistema de autenticação para controle de acesso dos usuários.

🚀 Funcionalidades
🔐 Sistema de Login
Autenticação de usuários com login e senha.
Validação de credenciais no banco de dados.
Criação de sessão após login bem-sucedido.
Bloqueio de acesso para usuários não autenticados.
Logout para encerramento da sessão.
👥 CRUD de Amigos
Create (Cadastrar)
Adicionar novos amigos ao sistema.
Armazenamento dos dados no banco de dados.
Read (Consultar)
Listar amigos cadastrados.
Visualizar informações dos registros.
Update (Alterar)
Editar informações de amigos existentes.
Atualizar dados no banco de dados.
Delete (Excluir)
Remover registros do sistema.
Confirmação da exclusão antes da remoção.
🏗️ Estrutura do Sistema

O projeto é composto pelos seguintes módulos:

Login: autenticação dos usuários.
CRUD: gerenciamento dos amigos cadastrados.
Banco de Dados: armazenamento das informações.
Sessões: controle de acesso e autenticação.
Organização de Arquivos: separação de responsabilidades para facilitar a manutenção.
📂 Arquivos Principais
conexaoBD.php
loginAction.php
logoutAction.php
verificarAcesso.php
acessoNegado.php

Esses arquivos são responsáveis pela conexão com o banco de dados, autenticação, encerramento de sessão e proteção das páginas do sistema.

🛠️ Tecnologias Utilizadas
PHP
MySQL
MySQLi
HTML
W3.CSS
Sessions (Sessões PHP)
🔒 Controle de Acesso

O sistema utiliza sessões para identificar usuários autenticados. Quando uma página protegida é acessada sem login válido, o usuário é redirecionado para a tela de acesso negado.

✅ Testes Realizados
Teste 1

Cenário: Login com usuário e senha corretos.

Resultado esperado: Acesso liberado ao sistema.

Teste 2

Cenário: Login com senha incorreta.

Resultado esperado: Acesso recusado.

Teste 3

Cenário: Logout seguido de tentativa de acesso direto a uma página protegida.

Resultado esperado: Acesso negado.

📚 Habilidades Desenvolvidas
Desenvolvimento de páginas web com PHP e HTML.
Integração entre aplicação e banco de dados.
Implementação de operações CRUD.
Desenvolvimento de sistema de autenticação.
Utilização de sessões para controle de acesso.
Organização de código em arquivos reutilizáveis.
Testes e correção de erros durante o desenvolvimento.
🎯 Conclusão

Este projeto integra autenticação de usuários, controle de acesso e operações CRUD em uma aplicação web conectada a banco de dados. Durante o desenvolvimento, foram aplicados conceitos fundamentais de PHP, MySQL, sessões e organização de código, proporcionando experiência prática em desenvolvimento web.

Desenvolvido por Gabriella Rodrigues 💻✨
