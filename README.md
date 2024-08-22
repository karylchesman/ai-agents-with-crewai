# AI Agents com CrewAI

Este projeto foi fruto do evento _IA na Prática_ organizado pela **Rocketseat**.

Neste projeto foi desenvolvido uma pequena aplicação que fará avaliações de ações na bolsa e então retornará para o usuário recomendações sobre a mesma. Desenvolvida baseada em **Agentes de AI**, conceito o qual esse projeto visa aplicar.

Neste projeto foi utilizado o **CrewAI**, que é um framework do python para trabalhar com Agentes de IA, 
e algumas ferramentas como o **YahooFinance** para coletar dados de ações na bolsa, **DuckDuckGo API** 
para realizar pesquisas e a **API do ChatGPT** como nosso LLM motor da aplicação.

### Instalação

#### Variáveis Ambiente

Crie um arquivo com nome ***.env*** na raiz do projeto com a chave `OPENAI_API_KEY` e coloque sua ***API Key***, conforme arquivo exemplo: ***.env.exemple***

#### Dependências

##### 1° forma

Se você possuir **Pyenv** e **Pipenv**, basta executar na raiz do projeto:

```sh
    $ pipenv install
    
```

Esse comando, irá criar um ambiente virtual e instalar todas as dependências.

##### 2° forma

Também há um arquivo requirements.txt no projeto, caso opte por uma instalação convencional, basta executar na raiz do projeto:

```sh
    $ pip install -r requirements.txt
    
```

### Executando

Para executar o projeto, estando com todas as dependências instaladas, basta executar na raiz do projeto:

```sh
    $ streamlit run crewai-stocks.py 

```