
# Chat com Documentos PDF (RAG)

Este projeto cria um chatbot que responde perguntas com base no conteúdo de documentos PDF carregados pelo usuário. Ele utiliza __LangChain__ para processamento e recuperação de informações e __Streamlit__ para a interface interativa.




## Funcionalidades


- __Upload de PDFs__: Os usuários podem carregar um ou mais documentos PDF.
- __Divisão de texto__: O conteúdo dos PDFs é dividido em partes menores (chunks) para melhor processamento.
- __Armazenamento vetorial__: As informações são armazenadas em uma base vetorial com Chroma.
- __Modelos OpenAI - Groq__: Suporte a modelos como GPT-3.5 e GPT-4 para responder perguntas ou modelos `Groq`.
- __Interface interativa__: Usuários fazem perguntas em um chat integrado e recebem respostas detalhadas.

## Tecnologias Utilizadas

- __Python__: Linguagem principal do projeto.
- __Streamlit__: Framework para construção da interface do usuário.
- __LangChain__: Biblioteca para integração de LLMs e agentes.
- __SQLite__: Banco de dados local para armazenar informações de estoque.
- __OpenAI GPT__: Modelos de linguagem para análise e respostas inteligentes.
- __Decouple__: Gerenciamento de variáveis de ambiente.

![image](https://github.com/user-attachments/assets/9d665796-fecf-4819-9ad7-725e661c1bbc)
