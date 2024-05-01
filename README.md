# Indexação e Consulta de dados com Azure AI Search
Esse módulo sobre a indexação e consulta de dados me lembrou um pouco o primeiro, com o Machine Learning. Pela "complexidade" de ser feito a criação do Azure Ai Search, esse passo a passo será breve e objetivo. 

Recomendo fortemente que visite a página que irei disponibilizar em referências e leia as instruções sobre a criação desses processos, pois, nessa instrução vai ter as informações detalhadas de cada processo. 

Primeiramente será necessário:
- Criar um recurso do Azure Ai Search, para indexar e consultar;

- Criar um recurso de Serviços da Azure, utilizado para fornecer serviços que vai enriquecer os dados na fonte de dados para gerar insights pela própria IA;

- Criar uma conta de armazenamento, com suas devidas configurações conforme sua necessidade. 

Após configurar todos esses recursos, você poderá anexar os documentos no armazenamento criado anteriormente, assim, podendo extrair insights dos documentos, o portal do azure fornece um auxilio para a importação de dados do armazenamento para o índice do Azure AI Search. 

Com a ajuda das instruções do Azure, podemos verificar e entender bem sobre cada opção na criação do índice. Após a criação do índice conseguimos importar os dados do armazenamento e consultar pelo Azure AI Search. 

## Referências: 
Para fazer esse passo a passo, utilizei como referência as aulas e a documentação da própria Azure:

- [Dio - Digital Innovation One](https://www.dio.me/)

- [Explore um índice do Azure AI Search (UI)](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#query-the-index)
