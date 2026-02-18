#  Sistema Acadêmico com Interface Gráfica

Aplicação desenvolvida em Python com interface gráfica em Tkinter e banco de dados SQLite para gerenciamento de trabalhos acadêmicos por professores e estudantes.

##  Objetivo
Simular o funcionamento de um sistema educacional real, aplicando conceitos de desenvolvimento de software como controle de usuários, persistência de dados e operações de CRUD.

##  Tecnologias Utilizadas
- Python
- Tkinter (Interface gráfica)
- SQLite (Banco de dados local)
- Programação Orientada a Objetos

##  Funcionalidades

###  Professores
- Visualizar todos os trabalhos cadastrados
- Editar ou deletar qualquer trabalho
- Gerar relatório completo
- Deletar todos os registros (com reinício de ID)

###  Estudantes
- Acessar apenas os trabalhos vinculados ao seu ID
- Adicionar novos trabalhos
- Editar seus próprios registros
- Remover seus próprios trabalhos
- Campos protegidos contra alteração de ID

##  Sistema de Login
O usuário escolhe o tipo de acesso ao iniciar o sistema.

**Professores**
Usuário: admin
Senha: admin

**Estudantes**
Usuários: 01 a 05
Senha: igual ao número do usuário
Exemplo: 01 → senha 01

##  Conceitos Aplicados
- CRUD completo com persistência em banco
- Integração entre interface gráfica e banco de dados
- Controle de permissões por tipo de usuário
- Organização lógica de aplicação desktop
- Estruturação de software com POO

##  Possíveis Melhorias
- Criptografia de senhas
- Cadastro dinâmico de usuários
- Exportação de relatórios em PDF
- Interface aprimorada
- Versão web futura

