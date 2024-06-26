# Web Scraping Site de Emprego Jaraguá do Sul
## Projeto Completo de Dados: da Engenharia ao Analytics

![imagem_01](./img/estrutura_projeto.png)

Este projeto foi concebido com dois propósitos:

1. Servir como um projeto útil e gerador de valor para usuários reais. A ideia era construir uma aplicação que pudesse ser utilizada por qualquer pessoa.

2. Desenvolver uma solução completa na área de dados, desde a extração de dados NoSQL, limpeza e tratamento, até a definição de schema, salvamento no banco, e, como cereja do bolo, nosso painel de análise de tudo o que construímos.

   Neste painel, além do design minimalista utilizando o Figma, desenvolvemos uma ferramenta para facilitar a busca por vagas de emprego na cidade de Jaraguá do Sul e região. É possível acessar informações da vaga com poucos cliques e até se candidatar a ela, tudo via Power BI.

   E para deixar tudo ainda mais completo, os dados são atualizados três vezes ao dia, garantindo assim a informação real e atualizada de cada vaga de emprego.

Link DataViz: [PowerBI](https://app.powerbi.com/view?r=eyJrIjoiMTgwNWIxOWQtMTkyYS00ODlhLWIwOTktYWFjNzQ0YTE5MzY1IiwidCI6IjVhY2IyMzk2LWE2ZWEtNDY2Yy1iYmZlLWQ5YTM5MzZmZjUzOCJ9)

![imagem_02](./img/tela_bi.png)

**Para rodar este projeto em sua máquina:**

Execute os comandos abaixo:

1. Crie um ambiente virtual: 
   - PowerShell: `python3.12 -m venv .venv`
   - Prompt de comando: `python -m venv .venv`

2. Ative o ambiente virtual:
   - PowerShell: `.\.venv\Scripts\Activate.ps1`
   - Prompt de comando: `.\.venv\Scripts\Activate.bat`

3. Instale as bibliotecas necessárias: `pip install -r requirements.txt`

4. Você precisa criar um arquivo .env para armazenar as variáveis de ambiente do seu banco. O nome dela deve ser: `URL_DATABASE_POSTGRES`

5. Para rodar o arquivo Python no ambiente virtual, no mesmo prompt aberto, execute: `python main.py`

6. Caso não queira trabalhar com schedule, basta remover os códigos de agendamento e invocar diretamente o método `start()` da classe.

7. Para sair do ambiente virtual, digite: `deactivate`
