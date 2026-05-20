# Diário do Bebê

Aplicação front-end estática para registro do dia a dia do bebê.

Este repositório contém um arquivo `index.html` que implementa a interface principal do Diário do Bebê. A documentação abaixo descreve o propósito do projeto, como executar localmente, estrutura do repositório, personalização, contribuições e informações de licença.

## Sumário

- Visão Geral
- Funcionalidades
- Pré-requisitos
- Executando localmente
- Estrutura do projeto
- Como usar
- Personalização
- Desenvolvimento
- Testes
- Contribuindo
- Licença
- Histórico de versões

## Visão Geral

O Diário do Bebê é uma aplicação simples, baseada em um único arquivo HTML, destinada a permitir que pais e cuidadores registrem eventos do bebê (mamar, sono, fraldas, observações etc.). O projeto atual é uma implementação front-end estática sem back-end.

## Funcionalidades

- Interface responsiva (HTML/CSS/JS).
- Registro de eventos no lado do cliente.
- Visualização e navegação entre entradas.
- Exportação/Importação (se implementado no index.html).

> Observação: As funcionalidades exatas dependem do conteúdo de `index.html`. Se desejar, posso inspecionar o arquivo e gerar documentação de referência da implementação (componentes, scripts, funções, variáveis globais, APIs usadas).

## Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari) com suporte a JavaScript.
- Para desenvolvimento: editor de texto (VSCode, Sublime, etc.).

## Executando localmente

1. Clone o repositório:

   git clone https://github.com/jeftericloud-ui/diario-bebe.git

2. Abra o arquivo `index.html` no navegador (duplo clique ou `File -> Open`).

3. Para um servidor local simples (opcional):

   - Usando Python 3:
     ```
     python -m http.server 8000
     ```
     Em seguida, acesse http://localhost:8000

   - Usando Live Server (VSCode): instale a extensão Live Server e clique em "Go Live".

## Estrutura do projeto

- index.html - Página principal da aplicação (UI, scripts e estilos podem estar embutidos ou referenciados).
- README.md - Documentação (este arquivo).
- CONTRIBUTING.md - Guia para contribuir.
- CHANGELOG.md - Histórico de versões.
- LICENSE - Licença do projeto.

## Como usar

- Abra `index.html` no navegador.
- Use os controles na interface para adicionar entradas do diário (alimentação, sono, trocas de fralda, observações).
- Procure por botões de exportar/importar caso queira salvar dados localmente.

## Personalização

- Estilos: modifique o CSS embutido em `index.html` ou extraia para um arquivo `.css` separado.
- Textos e idiomas: altere strings no HTML/JS para traduzir ou ajustar termos.
- Persistência: adicionar integração com um back-end (Firebase, API REST) para armazenar entradas remotamente.

## Desenvolvimento

- Recomendado: usar controle de versão (git) e criar branches para features/bugs.
- Para grandes mudanças, abra um Pull Request descrevendo a alteração.

## Testes

Este projeto não inclui uma suíte de testes automática. Para validação manual:

- Abra o app e verifique interações básicas (criar/editar/excluir entradas).
- Verifique compatibilidade entre navegadores e responsividade.

## Contribuindo

Veja `CONTRIBUTING.md` para orientações detalhadas sobre como contribuir com o projeto.

## Licença

Este projeto é fornecido sob a licença MIT. Veja o arquivo `LICENSE` para o texto completo.

## Histórico de versões

Consulte `CHANGELOG.md` para o histórico.
