# AI Agents com CrewAI

Este projeto foi fruto do evento _IA na Prática_ organizado pela **Rocketseat**.

Neste projeto foi desenvolvido uma aplicação que fará avaliações de ações na bolsa
e então retornar para o usuário recomendações sobre a mesma, que foi desenvolvida
baseada em **Agentes de AI**, conceito o qual esse projeto visa aplicar.

Neste projeto foi utilizado python como linguagem de programação, junto com **CrewAI**,
que é uma biblioteca do python para trabalhar com Agentes de IA, e algumas ferramentas
como o **YahooFinance** para coletar dados de ações na bolsa, **DuckDuckGo API** para realizar 
pesquisas e a **API do ChatGPT** como nosso LLM motor da aplicação.

#### Executar o projeto

Este projeto python foi construído com **Pyenv** e **Pipenv**, duas bibliotecas Python 
para gerenciamento de versões python e dependências de projetos com ambientes virtuais, 
respectivamente. Então para que você consiga rodar o projeto, você precisa dessas duas 
ferramentas corretamente instaladas e configuradas na sua máquina. Feito isso basta 
executar:

```python

    $ pipenv install

```

Além disso, é preciso criar um arquivo ***.env*** na raiz do projeto com a mesma estrutura do ***.env.exemple*** 
para que a lib **python-dotenv** consiga ler a chave de API necessária para usar o LLM.

Feito isso o projeto será instalado, configurado e estará pronto para ser executado.