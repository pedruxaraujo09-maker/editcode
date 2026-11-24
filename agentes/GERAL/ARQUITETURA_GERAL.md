# Arquitetura geral

## Estado

Este documento registra uma decomposição conceitual inicial derivada do escopo
do produto. Não é uma arquitetura de software validada: não há código,
diagramas de componentes concretos, contratos, protocolos escolhidos ou
tecnologias definidas no repositório.

## Subsistemas previstos

- **Interface:** experiência de edição e navegação, inicialmente voltada a
  Android.
- **Editor:** edição de texto e apresentação de conteúdo de código,
  independente da instalação de runtimes.
- **Sistema de arquivos:** acesso a arquivos e organização de projetos.
- **Sistema de linguagens:** gerenciamento opcional e separado de runtimes,
  compiladores, LSPs, formatadores e depuradores.
- **Terminal:** interação de linha de comando; modelo de execução ainda precisa
  ser pesquisado para as plataformas desejadas.
- **Extensões:** descoberta, validação, instalação e execução de extensões;
  compatibilidade com VS Code é uma hipótese a investigar.
- **Git e GitHub:** operações de controle de versão e integrações remotas.
- **Inteligência artificial:** provedores configuráveis e opcionais, sem
  dependência obrigatória do editor ou de um único serviço.
- **Segurança:** requisitos transversais para arquivos, pacotes, extensões,
  credenciais, processos e integrações.

## Relações conceituais

O editor deve permitir edição sem exigir um runtime. Recursos dependentes de
linguagem poderão integrar-se a componentes instalados separadamente. A
interface deverá apresentar os recursos dos subsistemas sem tornar a IA
obrigatória. Extensões e componentes instaláveis exigem validação de origem,
integridade, compatibilidade e permissões. Os mecanismos concretos de
comunicação, isolamento e armazenamento ainda não foram determinados.

## Decisões em aberto

- Linguagem, framework e estrutura de módulos para Android e eventual desktop.
- Implementação do editor e sua relação com WebView ou componentes nativos.
- Formato de pacotes, catálogo e mecanismo de instalação/remoção.
- Protocolos e gerenciamento de processos para LSP, terminal e depuradores.
- Modelo de compatibilidade, sandbox e APIs para extensões.
- Adaptadores de provedores de IA, armazenamento de configurações e credenciais.
- Limites e capacidades da integração Git/GitHub em Android.
- Fronteiras de segurança, permissões e estratégia de atualização.

Flutter, Kotlin, Monaco Editor, WebView, LSP e llama.cpp são candidatos
mencionados para pesquisa; nenhuma destas opções está aprovada. Cada escolha
deverá ser respaldada por pesquisa documentada no subsistema pertinente.
