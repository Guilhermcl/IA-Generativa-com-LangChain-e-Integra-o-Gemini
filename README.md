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

### Como Executar o Projeto

Siga as instruções abaixo para executar o projeto em seu ambiente local:

### 1. Clonar o Repositório
```bash
git clone https://github.com/Guilhermecl/IA-Generativa-com-LangChain-e-Gemini.git
cd IA-Generativa-com-LangChain-e-Gemini
## 2. Instalar Dependências

Instale as dependências do projeto utilizando o `pip`:

```bash
pip install -r requirements.txt

### config.py
GOOGLE_GEMINI_API_KEY = "SUA_CHAVE_GEMINI"
OPENAI_API_KEY = "SUA_CHAVE_OPENAI"
CLAUDE_API_KEY = "SUA_CHAVE_CLAUDE"

### Tecnologias Utilizadas

LangChain: Framework para integração de LLMs e ferramentas.

OpenAI GPT: Modelo de linguagem da OpenAI.

Google Gemini: Modelo de linguagem do Google.

Claude: Modelo de linguagem da Anthropic.

APIs externas: Integração com diversas APIs para funcionalidades adicionais.

### Contato
Se você tiver alguma dúvida ou sugestão, não hesite em me contactar através do LinkedIn ou GitHub.
linkedIn:<img width="836" height="829" alt="image" src="https://github.com/user-attachments/assets/8a6116c3-e85a-4e30-9260-201437f901e8" />


---

### Explicações sobre o `README.md`:

1. **Introdução e Funcionalidades**: A descrição inicial oferece uma visão clara das principais funcionalidades do projeto, destacando a integração de múltiplos LLMs e a capacidade de usar ferramentas e manter o contexto.

2. **Instruções de Execução**: Um guia claro e simples de como clonar, instalar dependências, configurar as chaves de API e rodar o projeto, incluindo exemplos de código.

3. **Estrutura de Diretórios**: Um mapeamento claro de como o projeto está organizado para facilitar a navegação para qualquer desenvolvedor que queira entender rapidamente a estrutura.

4. **Tecnologias Utilizadas e Licença**: A seção de tecnologias resume as principais bibliotecas e ferramentas utilizadas, além de fornecer informações sobre licenciamento e contribuições.

Este `README.md` fornece todas as informações necessárias para que outros desenvolvedores possam entender, configurar e contribuir para o seu projeto.
