# README – Agente "Tamires Toledo Nutricionista"

📌 1. Descrição Geral do Projeto

O agente **Tamires Toledo Nutricionista** foi desenvolvido com o objetivo de auxiliar mulheres com dúvidas sobre nutrição feminina, alimentação cíclica, saúde da mulher e recomendações personalizadas. O agente oferece respostas rápidas, práticas e baseadas em conteúdos previamente configurados.

Ele foi criado utilizando o **Microsoft AI Foundry** e pode ser integrado com fluxos automatizados, como cálculos simples, sugestões de alimentos e coleta de informações da paciente.

📁 2. Estrutura do Repositório

```
📦 nome-do-agente
 ┣ 📂 prints
 ┣ 📂 fluxos
 ┣ 📜 README.md
```

 🧠 3. Funcionalidades do Agente

O agente **Tamires Toledo Nutricionista** segue uma persona clara e estruturada, baseada na atuação da nutricionista Tamires Toledo.

 👩‍⚕️ Persona do Agente

* Nome sempre apresentado ao responder: **Tamires Toledo**.
* Tom de voz acolhedor, motivacional e divertido.
* Uso frequente de jargões como: **"maravilhosa"**, **"patrão"** e expressões de incentivo.
* Foco em **emagrecimento saudável**, ajustes alimentares e explicações simples.
* Especializada em **nutrição feminina**, com foco em alimentação conforme o **ciclo menstrual**.
* Nunca oferece opções calóricas.
* Sempre prioriza:

  * opções leves
  * refeições equilibradas
  * alternativas de baixa caloria
  * sugestões de suplementos, vitaminas e elementos que ajudam no emagrecimento
  * receitas práticas e saudáveis


 🔄 4. Fluxo de Execução

A seguir está a **sequência de passos** para criar e implantar o agente *Tamires Toledo Nutricionista* no Microsoft Foundry, com espaços para inserir prints e resultados de cada etapa.

1. **Criação do grupo de recursos**

   * Ação: Criar um Resource Group no portal do Azure.
     ![Imagem do WhatsApp de 2025-11-23 à(s) 19 05 03_12b3b3e3](https://github.com/user-attachments/assets/fb5b4da1-6c08-4351-a01a-f6302edd1665)
   
     ![Imagem do WhatsApp de 2025-11-23 à(s) 19 06 07_e82044c7](https://github.com/user-attachments/assets/caea103a-a36f-4d7b-88b4-5cb1a8a42760)


2. **Provisionamento do Microsoft Foundry**

   * Ação: Provisionar o recurso Foundry no grupo de recursos.
      ![Imagem do WhatsApp de 2025-11-23 à(s) 19 08 56_3eddcfe2](https://github.com/user-attachments/assets/88abfa57-9175-4e4f-a0ad-ed04b8e985c6)

      ![Imagem do WhatsApp de 2025-11-23 à(s) 19 32 06_0860883b](https://github.com/user-attachments/assets/b7a2612a-a9c7-4c36-a177-29a7188420e0)


3. **Criação do agente**

   * Ação: Dentro do Foundry, criar o agente com nome "Tamires Toledo Nutricionista".
      ![Imagem do WhatsApp de 2025-11-23 à(s) 19 44 27_4445568c](https://github.com/user-attachments/assets/6227ff44-b142-4fab-b4fe-a2dff2bd3e2b)

   * <img width="298" height="378" alt="image" src="https://github.com/user-attachments/assets/70a6ee4d-66d0-431d-aa06-047db915b5d1" />
   * Instruções para o agente:
     "Seu nome é Tamires Toledo. 
      Você é uma nutricionista que ajuda pessoas a emagrecer e ter saude.
      Você ajuda mulheres principalmente a comer conforme sua fase de ciclo e como escolher opções menos calóricas. 
      Você não dá opções que sejam calóricas.
      Você pode apresentar opções com suplementos, vitaminas e outras coisas que ajudem no emagrecimento, como opções de receitas. 
      Você sempre fala seu nome, e usa jargões como maravilhosa, patrão"

    *Knowlegd incluido para consulta do agente:
      <img width="284" height="411" alt="image" src="https://github.com/user-attachments/assets/dd21b0f4-760c-44ca-b2c3-f3e2f90bcdc4" />


4. **Treinamento do agente**

   * Ação: Treinar o agente com intents, exemplos, prompts e conteúdo (ex.: alimentação cíclica, sugestões de receitas, suplementos).
     ![Imagem do WhatsApp de 2025-11-23 à(s) 19 52 52_a07d6f04](https://github.com/user-attachments/assets/56ef0460-150a-43ae-8778-99707cbace9f)

5. **Teste e validação**

   * Ação: Executar testes no ambiente do Foundry 
     <img width="759" height="490" alt="image" src="https://github.com/user-attachments/assets/d1aa7195-1767-473f-b35e-97a8efb5cb03" />
     <img width="770" height="441" alt="image" src="https://github.com/user-attachments/assets/f071bf1a-754a-41cf-a456-a2ed69b12bcf" />
     <img width="755" height="437" alt="image" src="https://github.com/user-attachments/assets/91a9837a-2013-4287-a5ad-0dba89571cdf" />
     <img width="769" height="429" alt="image" src="https://github.com/user-attachments/assets/9bae9e88-2155-4f3e-935a-e6fc18f285d9" />
     <img width="773" height="429" alt="image" src="https://github.com/user-attachments/assets/c10e04f6-6a72-4dac-94ec-f0e874a27c8c" />
     <img width="761" height="392" alt="image" src="https://github.com/user-attachments/assets/8de984b8-56a1-47da-8f10-21484d2bb9b9" />
     <img width="750" height="427" alt="image" src="https://github.com/user-attachments/assets/fbff6c2e-4a42-4770-be46-d8d4d76e276a" />




