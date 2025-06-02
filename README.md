# Desafio: Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

Este repositório documenta meu aprendizado e a experiência adquirida durante o desafio de criar um copiloto com um fluxo de conversa personalizado, utilizando o Microsoft Copilot Studio. O foco foi explorar a customização de tópicos e o uso de IA Generativa para refinar as respostas.

## Resumo dos Aprendizados

A demonstração prática me permitiu aprofundar nos seguintes aspectos da criação de copilotos personalizados no Microsoft Copilot Studio:

### 1. Criação de um Copilot em Branco 🤖
* **O que aprendi:** Iniciar um copiloto "do zero" (em branco) oferece flexibilidade total para definir cada aspecto da interação. Diferentemente de usar modelos, aqui construímos toda a lógica conversacional.
* **Processo:** Entendi os passos para criar uma nova instância de copiloto sem tópicos pré-existentes, preparando o ambiente para a personalização completa.

### 2. Customização de um Tópico (Fluxo de Conversa) 💬
* **O que aprendi:** A customização de tópicos é o coração da personalização do copiloto. Isso envolve:
    * **Definição de Frases de Gatilho:** Como iniciar o tópico de forma precisa.
    * **Criação de Nós de Conversa:**
        * **Mensagens:** Para o copiloto fornecer informações.
        * **Perguntas:** Para coletar dados do usuário (e o uso de entidades para validar/extrair informações específicas).
        * **Condições (Ramificações):** Para criar lógicas de `if/else` no fluxo, direcionando a conversa com base nas respostas do usuário ou variáveis.
        * **Chamada de Ação:** (Se abordado na demo) Como integrar com Power Automate para ações mais complexas.
    * **Variáveis:** Como usar variáveis para armazenar e reutilizar informações ao longo da conversa dentro do tópico.
* **Experiência Prática:** Consegui criar/modificar um tópico para um cenário específico (ex: agendar um serviço, consultar status de pedido), definindo o diálogo passo a passo.

### 3. Personalização de uma Mensagem de Erro de Tópico ⚠️
* **O que aprendi:** Quando o copiloto não entende o usuário dentro de um tópico específico ou ocorre um erro no fluxo, é possível personalizar a mensagem de erro padrão para ser mais útil ou amigável.
* **Importância:** Uma boa mensagem de erro pode ajudar o usuário a reformular a pergunta ou guiá-lo para uma solução, melhorando a experiência geral.
* **Como fazer:** Explorei a seção de "Fallback" ou configurações de erro do tópico para inserir uma mensagem customizada.

### 4. Aumentar e Diminuir a Qualidade da Resposta com GenAI (Respostas Generativas)  искусственный интеллект ✨
* **O que aprendi:** O Copilot Studio permite usar IA Generativa para "aumentar" as conversas, gerando respostas mais dinâmicas e contextuais, especialmente quando conectado a uma base de conhecimento (como um site).
* **Controle de Qualidade/Criatividade:** A demonstração mostrou como é possível ajustar o "nível" ou "tom" da resposta gerada pela IA:
    * **Respostas mais diretas/factuais (diminuir):** Útil para quando se precisa de precisão e concisão.
    * **Respostas mais elaboradas/conversacionais (aumentar):** Pode ser usado para engajar mais o usuário, mas com cuidado para não perder o foco.
* **Aplicação:** Entendi como esse recurso pode ser usado para responder a perguntas que não estão explicitamente mapeadas em tópicos, usando uma fonte de dados como referência, e como refinar o comportamento dessa geração de resposta.

### Conclusão da Aprendizagem

Este desafio aprofundou minha compreensão sobre como construir fluxos de conversa realmente personalizados e como a IA Generativa pode enriquecer as interações do copiloto. A capacidade de iniciar do zero e moldar cada detalhe do diálogo, incluindo o tratamento de erros e o ajuste fino das respostas de IA, é fundamental para criar assistentes virtuais eficazes e alinhados com necessidades específicas.

---
