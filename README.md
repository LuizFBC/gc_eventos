# Documento de Navegação e Descrição do Projeto

## 1. Introdução
**Descrição Geral:** O Sistema de Gerenciamento de Eventos foi desenvolvido para permitir a criação, edição e administração eficiente de uma variedade de eventos, oferecendo uma experiência intuitiva para organizadores e participantes.

## 2. Visão Geral do Sistema
**Funcionalidades Principais:**
- Criação de eventos
- Participação em eventos
- Exclusão de eventos
- Autenticação de usuários (login)
- Cadastro de novos usuários 

**Usuários Alvo:** O sistema atende a dois principais grupos de usuários:
- Organizadores de eventos que desejam criar e gerenciar eventos.
- Participantes interessados em participar de eventos criados por outros usuários.

**Tecnologias Utilizadas:**
- Front-end desenvolvido utilizando Bootstrap para um design responsivo e amigável.
- Back-end implementado com o framework Laravel, fazendo uso da template engine Blade.

## 3. Fluxo de Navegação
**Fluxo de Navegação para Criar um Evento:**
1. Usuário Acessa a Plataforma:
   - Através da página de login, o usuário entra na plataforma.

2. Página de Login:
   - Insere suas credenciais (nome de usuário e senha).
   - O sistema verifica as credenciais e redireciona o usuário para a página inicial.

3. Página Inicial:
   - O usuário navega até a seção "Meus Eventos" ou "Criar Evento".

4. Criar Evento:
   - Clica no botão "Criar Novo Evento".
   - O sistema exibe um formulário de criação de evento.

5. Formulário de Criação de Evento:
   - Preenche campos obrigatórios como título, data e hora.
   - Adiciona descrição opcional.
   - Define local do evento.
   - Escolhe configurações de privacidade.
   - Clica em "Criar Evento".

6. Evento Criado:
   - Sistema valida os dados e cria o evento no banco de dados.
   - Confirmação visual do sucesso da criação.
   - Redirecionamento para a lista de eventos.

**Fluxo de Navegação para Participar de um Evento:**
1. Usuário Acessa a Plataforma:
   - Através da página de login, o usuário entra na plataforma.

2. Página de Login:
   - Insere suas credenciais (nome de usuário e senha).
   - O sistema verifica as credenciais e redireciona o usuário para a página inicial (dashboard).

3. Página Inicial:
   - Explora a lista de eventos disponíveis.

4. Lista de Eventos:
   - Clica em um evento específico para ver os detalhes.

5. Detalhes do Evento:
   - Lê informações como título, data, hora, local e descrição.
   - Clica em "Confirmar Presença".

6. Participação Confirmada:
   - Sistema registra a participação do usuário no evento.
   - Atualização dos detalhes do evento para refletir a presença do usuário.

## 4. Telas e Funcionalidades
- Tela de Login: Requer nome de usuário e senha, opção de "manter conectado".
- Tela de Cadastro: Solicita nome, e-mail e senha para o novo usuário.
- Lista de Eventos: Permite filtrar eventos e acessar detalhes como criador, participantes, datas e localização.
- Detalhes do Evento: Exibe informações detalhadas como data, local, descrição, participantes e organizador.
- Criação de Evento: Permite a criação de novos eventos, com detalhes como data, local, organizador e campos opcionais.
- Gerenciamento de Evento: Oferece opções para editar ou excluir eventos criados, bem como visualizar o número de participantes
