# Chat Streamlit com Gemini

Este projeto é um aplicativo de chat construído com Streamlit e o modelo Gemini da Google, projetado para funcionar como um tutor de programação amigável.

## Funcionalidades

* **Interface de Chat Interativa:** Permite aos usuários conversar com um assistente de IA.
* **Tutor de Programação:** O assistente foi projetado para explicar conceitos de programação de forma clara e simples, com exemplos.
* **Controle de Temperatura:** Os usuários podem ajustar a temperatura do modelo para controlar o nível de criatividade e aleatoriedade nas respostas.
* **Histórico de Chat:** O aplicativo mantém o histórico da conversa para fornecer contexto ao modelo.
* **Gerenciamento de Segredos:** Utiliza `streamlit.secrets` ou arquivos `.env` para gerenciar a chave da API de forma segura.

## Tecnologias Utilizadas

* **Streamlit:** Framework Python para criar aplicativos web interativos.
* **Google Generative AI (Gemini):** Modelo de linguagem da Google para gerar texto.
* **Python-dotenv:** Biblioteca para carregar variáveis de ambiente de arquivos `.env`.

## Requisitos

* Python 3.6+ (nesse em específico, usei o 3.12.7)
* Bibliotecas Python:
    * streamlit
    * google-generativeai
    * python-dotenv

## Instalação

1.  Clone o repositório:
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd <NOME_DO_REPOSITORIO>
    ```
2.  Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```
3.  Configure a chave da API:
    * Opção 1: Use o `streamlit.secrets` (recomendado para Streamlit Cloud).
    * Opção 2: Crie um arquivo `.env` na raiz do projeto e adicione sua chave da API:
        ```
        API_KEY=SUA_CHAVE_DA_API
        ```

## Como Usar

1.  Execute o aplicativo Streamlit:
    ```bash
    streamlit run app.py
    ```
2.  O aplicativo será aberto no seu navegador.
3.  Comece a conversar com o assistente de programação!

## Estrutura do Projeto

    Pergunta respondida com sucesso

## Estrutura do Projeto

* app.py >>> Arquivo principal do aplicativo Streamlit  1
* functions.py >>> Funções utilitárias, incluindo a função get_secret para gerenciar a chave da API
* requirements.txt >>> Lista de dependências do projeto
