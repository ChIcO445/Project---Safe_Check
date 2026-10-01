**SAFECHECK**

**DOCUMENTAÇÃO DA PRIMEIRA SPRINT**

Sprint 01

| Projeto | SafeCheck |
| :---- | :---- |
| **Sprint** | 01 |
| **Integrantes** | Francisco Lins; Rodrigo Pimente; Luiz Eduardo |
| **Versão** | 1.0 |
| **Data** | 01/10/2026 |

# **1\. Visão geral do projeto**

O SafeCheck é uma proposta de solução voltada à segurança digital de usuários de redes sociais, aplicativos de mensagens, comunidades online e outros ambientes digitais.

O sistema tem como objetivo oferecer mecanismos de prevenção, identificação, filtragem, bloqueio e denúncia de conteúdos, links, perfis e interações potencialmente maliciosos ou inadequados.

A primeira Sprint tem como finalidade transformar parte do backlog inicial em um primeiro incremento funcional, concentrando-se nas funcionalidades consideradas prioritárias para estabelecer o núcleo do produto.

# **2\. Sprint Planning**

## **2.1 Objetivo da Sprint**

O objetivo da Sprint 01 é desenvolver o primeiro conjunto de funcionalidades do SafeCheck relacionadas à prevenção, identificação de riscos, denúncia e proteção de conteúdo.

Foram selecionadas as seguintes histórias:

* US01 — Restrição  
* US02 — Denúncia  
* US03 — Suspeito  
* US05 — Link  
* US12 — Criador de Conteúdo

Essas histórias formam um núcleo funcional composto por prevenção, análise de risco, resposta a incidentes e proteção de publicações.

## **2.2 Meta da Sprint**

*Desenvolver um primeiro incremento do SafeCheck capaz de representar os principais fluxos de segurança digital, permitindo configurar restrições, registrar denúncias, identificar situações potencialmente suspeitas, analisar links e controlar o compartilhamento de conteúdos.*

# **3\. US01 — Restrição**

## **História de usuário**

*Como pai/mãe ou responsável, quero configurar restrições para determinados sites e aplicativos, para aumentar a segurança digital do meu filho.*

## **Objetivo**

Criar uma funcionalidade de controle parental capaz de armazenar regras de restrição e representar as configurações definidas pelo responsável.

## **Tarefas**

* Criar área de controle parental.  
* Criar perfil de responsável.  
* Permitir cadastro de sites e aplicativos.  
* Permitir definir uma regra de bloqueio.  
* Permitir alterar uma regra.  
* Permitir remover uma regra.  
* Registrar o estado da regra.  
* Informar limitações relacionadas a integrações externas.

| Prioridade | Must |
| :---- | :---- |
| **Status ao final da Sprint** |  |

# **4\. US02 — Denúncia**

## **História de usuário**

*Como utilizador do X, quero denunciar conteúdos potencialmente maliciosos de forma simples, para que a ocorrência possa ser encaminhada à plataforma responsável.*

## **Objetivo**

Criar um fluxo simples para que o usuário registre uma denúncia e forneça informações necessárias para sua análise.

## **Tarefas**

* Criar opção de iniciar denúncia.  
* Permitir selecionar o motivo.  
* Permitir anexar evidências quando disponíveis.  
* Registrar a ocorrência.  
* Criar identificador da denúncia.  
* Criar status da ocorrência.  
* Representar o encaminhamento para a plataforma quando houver integração autorizada.

| Prioridade | Must |
| :---- | :---- |
| **Status ao final da Sprint** |  |

# **5\. US03 — Suspeito**

## **História de usuário**

*Como utilizador do Facebook, quero receber avisos quando uma publicação apresentar características suspeitas, para decidir com mais segurança se devo interagir com ela.*

## **Objetivo**

Criar um mecanismo de alerta capaz de informar ao usuário quando forem identificados indicadores potencialmente relacionados a riscos.

## **Tarefas**

* Definir indicadores de risco.  
* Criar análise da publicação.  
* Criar alerta visual.  
* Informar que o resultado representa uma suspeita e não uma certeza.  
* Disponibilizar opções de saída, bloqueio ou denúncia.  
* Registrar a interação do usuário.

| Prioridade | Must |
| :---- | :---- |
| **Status ao final da Sprint** |  |

# **6\. US05 — Link**

## **História de usuário**

*Como utilizador do WhatsApp, quero que links potencialmente suspeitos sejam identificados, para evitar acessar conteúdos perigosos.*

## **Objetivo**

Permitir que o usuário forneça uma URL e receba uma análise baseada nos indicadores disponíveis.

## **Tarefas**

* Criar campo para inserção da URL.  
* Normalizar a URL.  
* Consultar indicadores disponíveis.  
* Classificar o nível de risco.  
* Apresentar justificativa resumida.  
* Orientar o usuário sobre uma ação segura.  
* Informar limitações da análise.

| Prioridade | Must |
| :---- | :---- |
| **Status ao final da Sprint** |  |

# **7\. US12 — Criador de Conteúdo**

## **História de usuário**

*Como criador de conteúdo, quero controlar quem pode compartilhar minhas publicações, para reduzir a possibilidade de uso malicioso do meu conteúdo.*

## **Objetivo**

Permitir que o criador configure preferências relacionadas ao público e ao compartilhamento de suas publicações.

## **Tarefas**

* Criar configuração de público.  
* Criar configuração de compartilhamento.  
* Registrar as preferências.  
* Informar limitações da plataforma.  
* Criar orientação para casos de uso indevido.  
* Permitir acesso às opções de denúncia quando disponíveis.

| Prioridade | Must |
| :---- | :---- |
| **Status ao final da Sprint** |  |

# **8\. Sprint Backlog Consolidado**

| ID | História | Principais tarefas | Prioridade | Status |
| :---- | :---- | :---- | :---- | :---- |
| US01 | Restrição | Controle parental e regras | Must | Concluída |
| US02 | Denúncia | Registro e encaminhamento | Must | Concluída |
| US03 | Suspeito | Identificação e alertas | Must | Concluída |
| US05 | Link | Análise e classificação de URL | Must | Concluída |
| US12 | Criador de Conteúdo | Controle de público e compartilhamento | Must | Concluída |

# **9\. Definition of Done — DoD**

A equipe definiu que uma história somente será considerada Pronta (Done) quando atender aos seguintes requisitos:

☑ Funcionalidade implementada.

☑ Fluxo principal funcionando.

☑ Critérios de aceitação atendidos.

☑ Funcionalidade testada.

☑ Problemas encontrados durante os testes corrigidos.

☑ Interface compreensível para o usuário.

☑ Limitações técnicas identificadas.

☑ Funcionalidade integrada ao restante do projeto.

☑ Resultado registrado na documentação da Sprint.

As funcionalidades relacionadas a plataformas externas não devem apresentar ações que o SafeCheck não possui autorização técnica para executar. Quando não houver integração disponível, o sistema deve orientar o usuário ou registrar a ocorrência.

# **10\. Execução da Sprint**

Durante a execução da Sprint, a equipe organizou o desenvolvimento em etapas.

## **10.1 Organização do backlog**

Inicialmente, foram analisadas as histórias priorizadas e seus respectivos critérios de aceitação. A equipe identificou que as cinco histórias possuem funcionalidades diferentes, mas podem compartilhar estruturas como registro de ocorrências, análise de risco, configurações, ações de bloqueio, mecanismos de denúncia e registro de informações.

## **10.2 Desenvolvimento das funcionalidades**

* US01: desenvolvimento do fluxo de configuração de restrições e representação das regras de controle parental.  
* US02: desenvolvimento do fluxo de denúncia, incluindo motivo, registro da ocorrência e acompanhamento do status.  
* US03: desenvolvimento do fluxo de alerta para situações potencialmente suspeitas.  
* US05: desenvolvimento do fluxo de inserção e análise de URLs.  
* US12: desenvolvimento do fluxo de controle de público e compartilhamento de publicações.

# **11\. Testes realizados**

| História | Cenário | Resultado esperado | Resultado |
| :---- | :---- | :---- | :---- |
| US01 — Restrição | Responsável configura uma restrição. | A regra deve ser salva e seu estado apresentado ao responsável. | Aprovado |
| US02 — Denúncia | Usuário encontra conteúdo potencialmente malicioso e inicia uma denúncia. | O sistema registra a ocorrência e apresenta seu status. | Aprovado |
| US03 — Suspeito | Uma publicação apresenta indicadores relacionados a phishing ou outro comportamento suspeito. | O sistema apresenta um alerta ao usuário. | Aprovado |
| US05 — Link | Usuário fornece uma URL para análise. | O sistema apresenta indicadores disponíveis e uma classificação de risco, informando limitações. | Aprovado |
| US12 — Criador | Criador configura as permissões de compartilhamento de uma publicação. | O sistema registra a preferência e informa eventuais limitações. | Aprovado |

# **12\. Impedimentos encontrados**

## **12.1 Dependência de plataformas externas**

Algumas funcionalidades dependem de mecanismos de terceiros, como APIs ou sistemas oficiais de denúncia. Por esse motivo, o protótipo deve representar essas ações sem afirmar que possui controle direto sobre plataformas externas.

## **12.2 Análise de risco**

Uma análise automática pode apresentar falsos positivos ou falsos negativos. Por isso, o SafeCheck utiliza a ideia de “potencialmente suspeito”, evitando afirmar que determinado conteúdo é definitivamente malicioso sem evidências suficientes.

## **12.3 Solução adotada**

Para lidar com essas limitações, o sistema apresenta os resultados como indicadores de risco, informa suas limitações e orienta o usuário sobre as ações disponíveis.

# **13\. Sprint Review**

Ao final da Sprint foi realizada uma revisão das funcionalidades desenvolvidas.

## **13.1 Funcionalidades apresentadas**

* Configuração de restrições.  
* Registro de denúncias.  
* Alertas para conteúdos potencialmente suspeitos.  
* Análise de links.  
* Controle de compartilhamento de publicações.

## **13.2 Resultado da Review**

As cinco histórias planejadas foram consideradas concluídas de acordo com a Definition of Done definida para a Sprint. O incremento produzido também mantém as limitações estabelecidas no backlog em relação às integrações com plataformas externas.

## **13.3 Feedback da Sprint Review**

Durante a revisão, foi identificado que o SafeCheck possui uma estrutura que pode ser expandida para outras plataformas e funcionalidades. Também foi observado que funcionalidades como bloqueio, denúncia e registro de incidentes podem compartilhar componentes entre diferentes plataformas.

## **13.4 Melhorias sugeridas**

* Melhorar a apresentação dos alertas.  
* Aprimorar os indicadores utilizados na análise de risco.  
* Ampliar as integrações.  
* Melhorar o acompanhamento das denúncias.  
* Adicionar outras plataformas previstas no backlog.

# **14\. Retrospectiva**

## **14.1 O que funcionou bem?**

* A definição prévia das histórias prioritárias facilitou a organização da Sprint.  
* A equipe trabalhou com funcionalidades relacionadas entre si, principalmente denúncia, análise de risco e registro de ocorrências.  
* As limitações das integrações externas foram consideradas desde o início.

## **14.2 O que poderia ser melhorado?**

* Algumas funcionalidades possuem dependências técnicas que precisam ser analisadas antes do desenvolvimento.  
* A divisão das tarefas pode ser melhorada para evitar concentração de determinadas atividades em apenas um integrante.

## **14.3 O que será feito na próxima Sprint?**

* Melhorar as funcionalidades existentes.  
* Corrigir problemas identificados nos testes.  
* Aprimorar a interface.  
* Avaliar novas histórias do backlog.  
* Analisar integrações necessárias.  
* Ampliar os mecanismos de segurança.

# **15\. Velocidade da Sprint**

Para esta documentação, foi utilizado um sistema de Story Points para representar o esforço relativo das histórias.

| História | Story Points |
| :---- | :---- |
| US01 — Restrição | 5 |
| US02 — Denúncia | 5 |
| US03 — Suspeito | 5 |
| US05 — Link | 3 |
| US12 — Criador de Conteúdo | 3 |
| **Total** | **21** |

Como todas as histórias planejadas foram concluídas:

**Velocidade da Sprint 01 \= 21 Story Points**

# **16\. Burndown da Sprint**

Considerando os 21 Story Points inicialmente planejados, o trabalho restante foi reduzido ao longo da Sprint.

| Dia | Trabalho restante |
| :---- | :---- |
| Dia 1 | 21 |
| Dia 2 | 17 |
| Dia 3 | 12 |
| Dia 4 | 6 |
| Dia 5 | 0 |

Representação do Burndown:

21 | ●

   |  \\

17 |   ●

   |    \\

12 |     ●

   |       \\

 6 |        ●

   |          \\

 0 |-----------●

      D1 D2 D3 D4 D5

# **17\. Métricas da Sprint**

| Métrica | Resultado |
| :---- | :---- |
| Histórias planejadas | 5 |
| Histórias concluídas | 5 |
| Histórias não concluídas | 0 |
| Story Points planejados | 21 |
| Story Points concluídos | 21 |
| Velocidade | 21 |
| Taxa de conclusão | 100% |

# **18\. Arquitetura funcional considerada**

| Componente | Função |
| :---- | :---- |
| **1\. Interface** | Recebe URLs, denúncias, preferências e solicitações de verificação. |
| **2\. Módulo de regras** | Aplica bloqueios, filtros, permissões e controles parentais. |
| **3\. Módulo de análise** | Avalia URLs, conteúdos e perfis utilizando os indicadores disponíveis. |
| **4\. Módulo de incidentes** | Registra denúncias, evidências, status e histórico. |
| **5\. Módulo de integração** | Comunica-se com APIs e mecanismos oficiais das plataformas quando houver autorização. |
| **6\. Segurança e privacidade** | Cuida de autenticação, autorização, minimização de dados e proteção das informações. |

# **19\. Requisitos não funcionais considerados**

| Requisito | Aplicação no SafeCheck |
| :---- | :---- |
| **Segurança** | Proteção das informações dos usuários e denúncias. |
| **Privacidade** | Utilização somente dos dados necessários. |
| **Usabilidade** | Alertas e ações apresentados de forma compreensível. |
| **Desempenho** | Verificações simples devem apresentar resposta adequada. |
| **Rastreabilidade** | Denúncias possuem registro e status. |
| **Confiabilidade** | Limitações das análises são informadas. |
| **Escalabilidade** | Estrutura preparada para futuras plataformas. |

# **20\. Resultado da Sprint**

Ao final da Sprint 01, o SafeCheck possui um primeiro conjunto de funcionalidades relacionadas diretamente ao seu objetivo principal.

* Prevenção: controle parental e restrições.  
* Detecção: identificação de características potencialmente suspeitas e análise de URLs.  
* Resposta: registro e encaminhamento de denúncias.  
* Proteção de conteúdo: controle de público e compartilhamento de publicações.

Essas áreas correspondem ao núcleo funcional definido para o primeiro incremento do produto.

# **21\. Próxima Sprint**

Após a conclusão da primeira Sprint, o backlog ainda possui outras histórias que podem ser desenvolvidas posteriormente:

* US04 — Ferramentas  
* US06 — Discord  
* US07 — TikTok  
* US08 — Chat Virtual  
* US09 — Lojas Virtuais  
* US10 — Menor de Idade  
* US11 — Instagram  
* US13 — Compra em Jogos Virtuais  
* US14 — YouTube  
* US15 — Google

Várias dessas funcionalidades podem aproveitar componentes desenvolvidos para o núcleo inicial, especialmente os fluxos de denúncia, bloqueio, registro de incidentes, evidências e encaminhamento.

# **22\. Conclusão**

A primeira Sprint do SafeCheck teve como objetivo transformar as histórias prioritárias do backlog em um primeiro incremento funcional do produto.

Foram selecionadas cinco histórias: US01 — Restrição, US02 — Denúncia, US03 — Suspeito, US05 — Link e US12 — Criador de Conteúdo.

O conjunto desenvolvido permite representar diferentes etapas do processo de segurança digital: prevenir situações de risco, identificar possíveis ameaças, orientar o usuário, registrar ocorrências e proteger conteúdos publicados.

A Sprint também permitiu estabelecer uma estrutura que pode ser expandida para novas plataformas e funcionalidades. A separação entre interface, regras, análise, incidentes, integração e segurança facilita a evolução do sistema.

Por fim, a Sprint Review e a Retrospectiva permitem que a equipe avalie tanto o produto desenvolvido quanto a forma de trabalho utilizada, criando uma base para o planejamento das próximas Sprints.