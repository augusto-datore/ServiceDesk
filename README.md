# Service Desk Acadêmico

Aplicativo web estático feito em HTML, CSS e JavaScript para demonstrar abertura, acompanhamento e atualização de chamados de suporte.

**Acesso online (GitHub Pages):** https://augusto-datore.github.io/ServiceDesk/

## Como executar

O projeto não precisa de servidor local, Node.js, Python ou instalação de dependências.

Abra o arquivo `index.html` em um navegador moderno.

## Funcionalidades

- Abertura de chamados com nome, e-mail, categoria, prioridade, título e descrição.
- Painel do analista para visualizar e selecionar chamados.
- Busca por número do chamado, título ou nome do solicitante.
- Alteração de status e prioridade.
- Registro da correção ou próxima ação.
- Histórico de alterações de cada chamado.
- Tela de histórico geral.
- Persistência dos dados no `localStorage` do navegador.
- Restauração dos dados de demonstração pela opção **Limpar base local**.

## Persistência dos dados

Os chamados são armazenados no `localStorage` do navegador, usando a chave `serviceDeskTickets`.

Isso significa que os dados ficam salvos no navegador e no perfil de usuário em que o sistema foi aberto. Eles não são enviados para um servidor e não são compartilhados automaticamente entre computadores ou navegadores.

A opção **Limpar base local** pede confirmação e restaura os chamados de demonstração. Ela não apaga os dados de outros navegadores ou dispositivos.

## Estrutura dos arquivos

- `index.html`: estrutura e conteúdo das telas.
- `styles.css`: aparência, layout e responsividade.
- `app.js`: interações, validações, histórico e persistência local.

## Observações

Este é um projeto acadêmico demonstrativo. O `localStorage` não substitui um banco de dados de produção, autenticação de usuários ou controle de acesso. Como não há backend, as informações ficam restritas ao navegador local.
