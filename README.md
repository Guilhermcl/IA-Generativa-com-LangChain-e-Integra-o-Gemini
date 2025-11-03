# Sistema de IA Generativa com LangChain e Integração de LLMs (Gemini, GPT, Claude)

Este projeto implementa um **sistema de IA generativa** utilizando a biblioteca **LangChain** para integrar múltiplos **Modelos de Linguagem (LLMs)**, como **Google Gemini**, **GPT** e **Claude**, permitindo flexibilidade, escalabilidade e integração com várias ferramentas. O sistema foi projetado para oferecer uma experiência de interação dinâmica, reusável e com manutenção de contexto entre as conversas.

## Funcionalidades Principais

- **Troca Dinâmica entre LLMs**: O sistema permite alternar facilmente entre diferentes modelos de linguagem (Google Gemini, GPT, Claude) com apenas algumas mudanças no código.
- **Execução de Operações em Sequência**: Suporta a encadeamento de múltiplas operações, como cálculos, consultas a APIs externas, e buscas na web, criando um fluxo contínuo.
- **Ferramentas Integradas**: O sistema pode utilizar ferramentas como **calculadora**, **busca na web**, e **APIs externas** para expandir as capacidades das LLMs.
- **Manutenção de Contexto e Histórico**: O sistema mantém o contexto entre conversas e armazena o histórico de interações de forma persistente.
- **Reutilização de Prompts**: Uso de templates de prompts que podem ser reutilizados e parametrizados para maior flexibilidade.
- **Versionamento de Prompts**: Sistema de versionamento para controle e evolução dos prompts, garantindo uma abordagem iterativa e adaptável.

## Estrutura do Projeto

Abaixo estão as principais partes do sistema e sua funcionalidade:

1. **Interface com LLMs**:
   - Abstração da integração com modelos como **Google Gemini**, **GPT** e **Claude**. Cada LLM pode ser trocado com mínima modificação no código.
2. **Ferramentas e APIs**:
   - Implementação de funcionalidades como uma **calculadora**, **busca na web**, e integração com APIs externas (ex: APIs de notícias ou informações em tempo real).
3. **Persistência de Dados**:
   - Utiliza um banco de dados simples para armazenar o histórico de chats e manter o contexto entre as conversas.
  
#Práticas:
#Chat
  <img width="1848" height="464" alt="image" src="https://github.com/user-attachments/assets/fa89bcb1-45b0-43f1-b1fd-2c689c0359c4" />
  # Memória
  <img width="1256" height="877" alt="image" src="https://github.com/user-attachments/assets/adf0f950-c1d1-4026-88ae-509892e69734" />

  
