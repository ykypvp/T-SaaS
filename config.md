# Introdução
## O que é o T-SaaS
    "O T-SaaS é uma interface dinâmica (Dashboard) que utiliza um motor de renderização baseado em arquivos Markdown. Ele permite criar interfaces complexas apenas editando este arquivo de configuração, sem a necessidade de recompilar o código fonte."

## Arquitetura do Sistema
    "O núcleo do sistema funciona através de um parser que identifica headers de primeiro nível `#` como itens de menu e headers de segundo nível `##` como blocos de conteúdo reativos."

# Guia de Uso
## Como Configurar Abas
    "Para criar uma nova aba no menu lateral, utilize o prefixo `#` seguido do nome da aba. Todo o conteúdo abaixo desse header pertencerá a essa seção até que um novo header de nível 1 seja declarado."

## Criação de Blocos
    "Dentro de cada aba, você pode criar múltiplos blocos de informação utilizando `##`. O texto do bloco deve estar entre aspas duplas no arquivo de configuração para ser renderizado corretamente na interface."

# Comandos e Ações
## Integração de Botões
    "Os botões são declarados usando colchetes e aspas. O formato é `["Nome do Botão : função"]`. As funções devem estar mapeadas dentro do objeto `ACTIONS` no arquivo `index.html`."

## Funcionalidades de Código
    "O sistema suporta realce de sintaxe simples para comandos de terminal. Qualquer texto entre crases será formatado como bloco de código clicável para cópia automática."

# Código Fonte
## index.html
    "O código está no seguinte link: `https://justpaste.it/gygoq`"