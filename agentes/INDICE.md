# Índice da base de conhecimento

## Propósito e estado atual

Esta pasta contém a documentação técnica do PROGRASO, organizada por contexto
geral e subsistema. É a referência para compreender o estado conhecido, as
decisões ainda pendentes e as evidências registradas. Ela não comprova que uma
funcionalidade foi implementada.

Na inspeção inicial, o repositório continha somente um README com o título
`editcode`; não havia código, testes, pesquisas ou decisões técnicas anteriores
para registrar. Os documentos abaixo estabelecem o contexto solicitado, sem
afirmar que as funcionalidades planejadas já existem. Nenhuma tecnologia foi
selecionada.

## Documentos gerais

- [Descrição do projeto](GERAL/DESCRICAO_DO_PROJETO.md): objetivo, escopo
  funcional pretendido, restrições conhecidas e estado observado.
- [Regras gerais](GERAL/REGRAS_GERAIS.md): regras obrigatórias para agentes e
  critérios de integridade da documentação.
- [Arquitetura geral](GERAL/ARQUITETURA_GERAL.md): subsistemas previstos,
  responsabilidades em nível conceitual e decisões ainda abertas.
- [Roadmap](GERAL/ROADMAP.md): sequência de trabalho proposta; não representa
  funcionalidades concluídas.
- [Como trabalhar](GERAL/COMO_TRABALHAR.md): procedimento para consultar,
  alterar, validar e atualizar a base documental.

## Índices de subsistemas

Cada índice descreve o escopo do subsistema, os documentos disponíveis e o que
ainda não foi pesquisado ou decidido.

- [Editor](EDITOR/INDICE.md)
- [Sistema de arquivos](SISTEMA_DE_ARQUIVOS/INDICE.md)
- [Terminal](TERMINAL/INDICE.md)
- [Sistema de linguagens](SISTEMA_DE_LINGUAGENS/INDICE.md)
- [Extensões](EXTENSOES/INDICE.md)
- [Inteligência artificial](INTELIGENCIA_ARTIFICIAL/INDICE.md)
- [Git e GitHub](GIT_E_GITHUB/INDICE.md)
- [Interface](INTERFACE/INDICE.md)
- [Segurança](SEGURANCA/INDICE.md)

## Organização de cada subsistema

As pastas `PESQUISA/`, `PLANEJAMENTO/`, `IMPLEMENTACAO/` e `TESTES/` estão
reservadas para registros com conteúdo real. Ainda não existem relatórios
nessas categorias. Pastas vazias são mantidas por arquivos `.gitkeep`, que não
são documentação.

Consulte apenas os documentos pertinentes à tarefa: as regras e o procedimento
gerais, a descrição ou arquitetura geral quando necessárias e o índice e
registros do subsistema afetado. Leia os documentos listados em um índice antes
de alterá-los. Se houver divergência entre documentação e código, registre-a
em vez de presumir qual dos dois está correto.

## Estado da documentação

- Documentos gerais iniciais: criados.
- Índices de subsistemas: criados.
- Pesquisas técnicas com fontes verificadas: ainda não realizadas.
- Planejamentos de implementação por subsistema: ainda não criados.
- Histórico de implementação e resultados de testes: inexistentes; nenhum
  aplicativo foi implementado ou validado.
- Tecnologias candidatas mencionadas no escopo: Flutter, Kotlin, Monaco Editor,
  WebView, LSP e llama.cpp. São candidatas para investigação, não decisões.

Atualize este índice e os índices afetados quando documentos forem adicionados,
renomeados ou alterados de forma relevante.
