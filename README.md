# Extraindo e analisando notícias da [Infonet](https://infonet.com.br)
Com o objetivo de coletar dados de notícias publicadas na Infonet, um grande portal de notícias do estado de Sergipe, foi construído o `Infonet Scraping.ipynb`. O Jupyter Notebook que se encontra nesse repositório conta com técnicas de Web Scraping para a extração e armazenamento de dados das notícias, tais como **título**, **resumo** e **autoria**.

Para além da extração dos dados, foi implementado um campo específico dentro do Notebook para a análise de voz verbal nas manchetes. Esse campo possibilita a inserção de qual tipo de voz verbal os verbos da manchete apresentam, _ativa_ ou _passiva_.

## Teste e validação

Visando o teste e validação da ferramenta, foram coletadas e analisadas 100 notícias, divididas em duas buscas no site da [infonet](https://infonet.com.br). No campo de pesquisa do site, foram feitas as seguintes buscas:
* "Homem é"
* "Mulher é"


Com os links resultantes da pesquisa, foi realizado o scraping e armazenamento dos dados coletados. Após a extração, foram realizadas as análises das manchetes para identificação da voz verbal. 
Os resultados dos testes encontram-se nas pastas `dados` e `análises`.
