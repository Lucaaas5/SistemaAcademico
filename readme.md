Sistema Acadêmico com Interface Gráfica (Tkinter)

Aplicação educacional desenvolvida em Python com interface gráfica utilizando Tkinter e banco de dados SQLite, permitindo o gerenciamento de trabalhos acadêmicos por professores e estudantes.

O projeto foi criado com fins de aprendizado prático, simulando funcionalidades reais de um sistema educacional com controle de acesso por tipo de usuário.

 Objetivo do Projeto

Aplicar conceitos de desenvolvimento de software na construção de um sistema completo, incluindo:

Interface gráfica desktop

Persistência de dados

Controle de usuários

Operações de CRUD

Regras de negócio distintas por perfil de acesso

 Tecnologias Utilizadas

Python

Tkinter → Interface gráfica

SQLite → Banco de dados local

Programação Orientada a Objetos

CRUD (Create, Read, Update, Delete)

 Perfis de Usuário

O sistema possui dois níveis de acesso com permissões diferentes:

 Professores

Visualizar todos os trabalhos cadastrados

Editar ou deletar qualquer trabalho

Gerar relatório completo

Deletar todos os registros (com reinício automático dos IDs)

 Estudantes

Visualizar apenas os trabalhos associados ao seu ID

Adicionar novos trabalhos

Editar seus próprios registros

Remover seus próprios trabalhos

Campos de ID protegidos contra alteração

Tela de Login

O sistema inicia com uma tela de autenticação onde o usuário escolhe o tipo de acesso:

Professores
Usuário: admin
Senha: admin

Estudantes
Usuários: 01 a 05
Senha: igual ao número do usuário
Exemplo: 01 → senha 01

Conceitos Aplicados

Este projeto permitiu exercitar:

Desenvolvimento de aplicações desktop

Integração entre interface gráfica e banco de dados

Controle de permissões por usuário

Estruturação de código orientado a objetos

Manipulação e persistência de dados com SQLite

Simulação de sistema real de gerenciamento acadêmico

 Possíveis Melhorias Futuras

Criptografia de senhas

Cadastro dinâmico de usuários

Exportação de relatórios em PDF

Interface mais moderna (CustomTkinter ou PyQt)

Transformação em aplicação web (Flask/Django)
