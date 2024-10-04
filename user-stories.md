## **Histórias de Usuário**

  

### **ID:**

HU-001

### **Título:**

Usuário inicia sessão de perguntas com o chatbot

### **Descrição:**

Como **usuário**, eu quero **iniciar uma sessão de perguntas com o chatbot** para que **eu possa fazer perguntas sobre treinos e atividades físicas e receber respostas rápidas e precisas**.

### **Critérios de Aceitação:**

#### Cenário 1: Início de sessão com sucesso

-   **Dado** que o usuário acessa a interface do chatbot,
-   **Quando** o usuário inicia a sessão de chat,
-   **Então** o chatbot deve estar disponível e pronto para receber perguntas.

#### Cenário 2: Falha na conexão do chatbot

-   **Dado** que o usuário tenta iniciar a sessão de chat,
-   **Quando** há uma falha na conexão com o chatbot,
-   **Então** uma mensagem de erro deve ser exibida informando a indisponibilidade do chatbot,
-   **E** o usuário deve ser informado para tentar novamente mais tarde.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

5 Story Points

### **Dependências:**

-   Integração com o sistema de comunicação do chatbot.

### **Notas/Comentários Adicionais:**

-   O chatbot deve estar disponível 24 horas por dia para responder às perguntas dos usuários.

---
### **ID:**

HU-002

### **Título:**

Usuário envia uma pergunta sobre treinos ou esportes

### **Descrição:**

Como **usuário**, eu quero **enviar uma pergunta sobre treinos ou esportes para o chatbot** para que **eu possa obter orientações ou sugestões relacionadas à atividade física de interesse**.

### **Critérios de Aceitação:**

#### Cenário 1: Pergunta enviada com sucesso

-   **Dado** que o usuário está em uma sessão ativa com o chatbot,
-   **Quando** o usuário envia uma pergunta válida sobre treinos ou esportes,
-   **Então** o chatbot deve reconhecer a pergunta e gerar uma resposta apropriada.

#### Cenário 2: Pergunta inválida ou incompreensível

-   **Dado** que o usuário está em uma sessão ativa com o chatbot,
-   **Quando** o usuário envia uma pergunta inválida ou incompreensível,
-   **Então** o chatbot deve solicitar mais informações ou pedir reformulação da pergunta.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

5 Story Points

### **Dependências:**

-   Integração com o módulo de processamento de linguagem natural.

### **Notas/Comentários Adicionais:**

-   O chatbot deve ser capaz de lidar com perguntas simples e complexas, fornecendo respostas diretas ou pedindo esclarecimentos quando necessário.

---
### **ID:**

HU-003

### **Título:**

Usuário recebe resposta com sugestão de treino

### **Descrição:**

Como **usuário**, eu quero **receber uma resposta com sugestão de treino do chatbot** para que **eu possa seguir uma rotina de atividades físicas adequada à minha necessidade ou esporte de interesse**.

### **Critérios de Aceitação:**

#### Cenário 1: Resposta com sugestão de treino bem-sucedida

-   **Dado** que o usuário enviou uma pergunta relacionada a treinos ou esportes,
-   **Quando** o chatbot processa a pergunta,
-   **Então** o chatbot deve fornecer uma sugestão de treino que seja relevante ao esporte ou objetivo mencionado pelo usuário.

#### Cenário 2: Sugestão de treino genérica por falta de detalhes

-   **Dado** que o usuário enviou uma pergunta com poucos detalhes ou ambígua,
-   **Quando** o chatbot processa a pergunta,
-   **Então** o chatbot deve fornecer uma sugestão de treino genérica e solicitar mais informações para ajustar melhor a resposta.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

8 Story Points

### **Dependências:**

-   Integração com base de dados de exercícios e treinos.

### **Notas/Comentários Adicionais:**

-   As sugestões de treino devem incluir descrições claras das atividades recomendadas e podem ser acompanhadas de orientações sobre a duração e frequência das sessões.

---
### **ID:**

HU-004

### **Título:**

Usuário visualiza sugestões de atividades físicas baseadas na pergunta enviada

### **Descrição:**

Como **usuário**, eu quero **visualizar sugestões de atividades físicas com base na pergunta que enviei** para que **eu possa ter uma variedade de opções de treino para escolher**.

### **Critérios de Aceitação:**

#### Cenário 1: Sugestões de atividades físicas exibidas com sucesso

-   **Dado** que o usuário recebeu uma resposta do chatbot com sugestões de treino,
-   **Quando** o usuário solicita visualizar as sugestões,
-   **Então** o chatbot deve exibir uma lista clara e organizada de atividades físicas relacionadas à pergunta original.

#### Cenário 2: Nenhuma sugestão disponível

-   **Dado** que o usuário fez uma pergunta sobre atividades físicas,
-   **Quando** não há sugestões disponíveis devido a falta de informações ou dados,
-   **Então** o chatbot deve informar ao usuário que não há sugestões disponíveis e sugerir que forneça mais detalhes.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

5 Story Points

### **Dependências:**

-   Integração com o sistema de exibição de sugestões e interações do chatbot.

### **Notas/Comentários Adicionais:**

-   As sugestões devem ser apresentadas de forma acessível e visualmente atraente, com informações suficientes para ajudar o usuário a tomar decisões sobre qual atividade praticar.

---
### **ID:**

HU-005

### **Título:**

Usuário solicita mais detalhes ou exemplos sobre o treino sugerido

### **Descrição:**

Como **usuário**, eu quero **solicitar mais detalhes ou exemplos sobre o treino sugerido pelo chatbot** para que **eu possa entender melhor como realizar os exercícios corretamente e maximizar meus resultados**.

### **Critérios de Aceitação:**

#### Cenário 1: Detalhes adicionais fornecidos com sucesso

-   **Dado** que o usuário recebeu uma sugestão de treino,
-   **Quando** o usuário solicita mais detalhes ou exemplos sobre o treino,
-   **Então** o chatbot deve fornecer informações adicionais, como instruções, dicas de execução e possíveis variações dos exercícios.

#### Cenário 2: Falta de informações adicionais

-   **Dado** que o usuário solicita mais detalhes sobre um treino específico,
-   **Quando** não há informações adicionais disponíveis para o exercício sugerido,
-   **Então** o chatbot deve informar que não há mais detalhes disponíveis e sugerir alternativas ou exercícios similares.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

5 Story Points

### **Dependências:**

-   Integração com o banco de dados de informações e instruções dos exercícios.

### **Notas/Comentários Adicionais:**

-   As informações adicionais devem incluir instruções claras e, se possível, links para vídeos ou imagens que demonstrem a execução correta dos exercícios.

---
### **ID:**

HU-006

### **Título:**

Usuário interrompe a interação a qualquer momento

### **Descrição:**

Como **usuário**, eu quero **interromper a interação com o chatbot a qualquer momento** para que **eu possa encerrar a conversa sem complicações e retornar quando desejar**.

### **Critérios de Aceitação:**

#### Cenário 1: Interrupção bem-sucedida da interação

-   **Dado** que o usuário está em uma sessão ativa com o chatbot,
-   **Quando** o usuário decide interromper a interação,
-   **Então** o chatbot deve reconhecer a solicitação de interrupção e finalizar a sessão de forma amigável.

#### Cenário 2: Retorno ao chatbot após a interrupção

-   **Dado** que o usuário interrompeu a interação anteriormente,
-   **Quando** o usuário retorna para interagir novamente com o chatbot,
-   **Então** o chatbot deve iniciar uma nova sessão sem reter informações da conversa anterior.

### **Prioridade:**

Média

### **Estimativa de Esforço:**

3 Story Points

### **Dependências:**

-   Integração com o sistema de gerenciamento de sessões do chatbot.

### **Notas/Comentários Adicionais:**

-   O chatbot deve ser capaz de encerrar a conversa de maneira cortês, oferecendo um agradecimento pela interação e convidando o usuário a retornar quando desejar.

---
### **ID:**

HU-007

### **Título:**

Usuário consulta o histórico de interações

### **Descrição:**

Como **usuário**, eu quero **consultar o histórico de interações com o chatbot** para que **eu possa revisar perguntas anteriores e respostas recebidas, ajudando-me a acompanhar meu progresso e encontrar informações úteis**.

### **Critérios de Aceitação:**

#### Cenário 1: Histórico de interações exibido com sucesso

-   **Dado** que o usuário está em uma sessão ativa com o chatbot,
-   **Quando** o usuário solicita visualizar o histórico de interações,
-   **Então** o chatbot deve exibir uma lista cronológica das perguntas feitas e as respectivas respostas recebidas.

#### Cenário 2: Histórico vazio

-   **Dado** que o usuário não teve interações anteriores,
-   **Quando** o usuário solicita visualizar o histórico de interações,
-   **Então** o chatbot deve informar que não há interações registradas e sugerir que o usuário faça uma nova pergunta.

### **Prioridade:**

Média

### **Estimativa de Esforço:**

3 Story Points

### **Dependências:**

-   Integração com o sistema de armazenamento de dados das interações do usuário.

### **Notas/Comentários Adicionais:**

-   O histórico deve ser apresentado de forma clara e organizada, com a opção de o usuário acessar rapidamente respostas úteis ou rever perguntas anteriores.

---
### **ID:**

HU-008

### **Título:**

Usuário recebe respostas em linguagem natural

### **Descrição:**

Como **usuário**, eu quero **receber respostas em linguagem natural do chatbot** para que **eu possa entender facilmente as informações e orientações sobre treinos e atividades físicas**.

### **Critérios de Aceitação:**

#### Cenário 1: Resposta em linguagem natural bem-sucedida

-   **Dado** que o usuário enviou uma pergunta ao chatbot,
-   **Quando** o chatbot processa a pergunta e gera uma resposta,
-   **Então** a resposta deve ser apresentada em uma linguagem clara, acessível e fácil de entender.

#### Cenário 2: Resposta com linguagem técnica excessiva

-   **Dado** que o usuário enviou uma pergunta ao chatbot,
-   **Quando** a resposta gerada contiver termos técnicos ou jargões excessivos,
-   **Então** o chatbot deve oferecer uma explicação alternativa em linguagem mais simples ou solicitar se o usuário deseja mais esclarecimentos.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

5 Story Points

### **Dependências:**

-   Integração com o sistema de processamento de linguagem natural (História HU-002).

### **Notas/Comentários Adicionais:**

-   O chatbot deve ser projetado para adaptar a complexidade da linguagem de acordo com o contexto da pergunta, assegurando que as respostas sejam compreensíveis para usuários com diferentes níveis de conhecimento sobre atividades físicas.

---
### **ID:**

HU-009

### **Título:**

Usuário pode dar continuidade em um assunto

### **Descrição:**

Como **usuário**, eu quero **dar continuidade em um assunto já discutido com o chatbot** para que **eu possa aprofundar meu entendimento ou fazer perguntas adicionais relacionadas ao tema**.

### **Critérios de Aceitação:**

#### Cenário 1: Continuidade de assunto com sucesso

-   **Dado** que o usuário está em uma sessão ativa com o chatbot e discutiu um assunto anteriormente,
-   **Quando** o usuário faz uma nova pergunta ou comentário relacionado ao tema já discutido,
-   **Então** o chatbot deve reconhecer o contexto e fornecer uma resposta coerente e relevante, continuando a conversa.

#### Cenário 2: Falha ao continuar um assunto

-   **Dado** que o usuário tenta continuar um assunto,
-   **Quando** o chatbot não consegue reconhecer a continuidade do tema,
-   **Então** o chatbot deve solicitar que o usuário esclareça ou forneça mais informações sobre o que deseja discutir.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

5 Story Points

### **Dependências:**

-   Integração com o sistema de gerenciamento de contexto e histórico de conversas.

### **Notas/Comentários Adicionais:**

-   O chatbot deve ser capaz de manter a continuidade de tópicos relevantes para melhorar a experiência do usuário e proporcionar uma interação mais fluida e natural.

---
### **ID:**

HU-010

### **Título:**

Usuário recebe orientações sobre como formular perguntas mais eficazes

### **Descrição:**

Como **usuário**, eu quero **receber orientações sobre como formular perguntas mais eficazes para o chatbot** para que **eu possa obter respostas mais precisas e úteis relacionadas a treinos e atividades físicas**.

### **Critérios de Aceitação:**

#### Cenário 1: Orientações fornecidas com sucesso

-   **Dado** que o usuário solicita dicas sobre como formular perguntas,
-   **Quando** o chatbot processa a solicitação,
-   **Então** o chatbot deve fornecer orientações claras e práticas sobre como fazer perguntas que ajudem a obter respostas mais relevantes.

#### Cenário 2: Exibição de exemplos de perguntas

-   **Dado** que o usuário está em uma sessão ativa com o chatbot,
-   **Quando** o usuário pede exemplos de perguntas eficazes,
-   **Então** o chatbot deve listar exemplos de perguntas que demonstram a formulação adequada para obter melhores respostas.

### **Prioridade:**

Média

### **Estimativa de Esforço:**

3 Story Points

### **Dependências:**

-   Integração com o sistema de sugestões e orientações do chatbot.

### **Notas/Comentários Adicionais:**

-   As orientações devem ser adaptáveis e levar em consideração a diversidade de temas e interesses dos usuários, ajudando-os a melhorar a qualidade das interações com o chatbot.
