# Descrição do projeto

## Objetivo

O PROGRASO pretende ser uma IDE/editor de código com foco inicial em Android e
possibilidade de expansão futura para desktop. A prioridade inicial é
compreender, pesquisar e documentar os subsistemas antes de escolher
tecnologias ou implementar o aplicativo.

## Escopo funcional pretendido

O produto poderá oferecer:

- edição de código em Android;
- gerenciamento de arquivos e projetos;
- terminal;
- componentes de linguagens instaláveis sob demanda;
- extensões instaláveis de fontes como GitHub;
- integração com Git e GitHub;
- integração opcional de inteligência artificial, desacoplada do editor, com
  suporte a modelos locais, serviços externos e endpoints próprios.

São objetivos e requisitos iniciais, não funcionalidades existentes.

### Sistema de linguagens

Nenhuma linguagem ou runtime deverá ser obrigatória no APK. A edição de arquivos
deve ser possível sem instalar o runtime correspondente. Quando necessário, o
produto poderá oferecer a instalação separada de componentes como runtime,
compilador, LSP, formatador e depurador. Instalar ou remover esses componentes
não deve apagar projetos do usuário. Catálogos oficiais ou comunitários
precisam ser investigados quanto à origem, integridade, compatibilidade e
permissões.

### Extensões

Deve ser investigada a possibilidade de compatibilidade com extensões do Visual
Studio Code. Não se presume compatibilidade total: APIs, runtimes e dependências
precisam ser estudados antes de qualquer promessa.

### Inteligência artificial

A IA é opcional e deve permanecer desacoplada do editor. Não se assume
dependência de um único provedor.

## Restrições e tecnologias em aberto

Flutter, Kotlin, Monaco Editor, WebView, LSP e llama.cpp foram considerados
candidatos, mas nenhum foi pesquisado ou validado neste repositório como
decisão definitiva. A escolha de tecnologias deve ser precedida de pesquisa
documentada e evidências.

Não criar diretórios de código nem instalar dependências enquanto as pesquisas
e decisões necessárias não tiverem sido realizadas.

## Estado observado do repositório

Na inspeção inicial havia somente o README com o título `editcode`. Não havia
código do aplicativo, pesquisas, planejamento técnico, testes ou decisões
arquiteturais registrados. Esta documentação descreve o objetivo solicitado e
separa explicitamente esse objetivo do estado implementado.
