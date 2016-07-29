# Recomendação na Prática
## Meetup Machine Learning Porto Alegre
Juarez da Silva Bochi 

Júlia Kikuye Kambara da Silva

Esta apresentação foi feita para o [Meetup de Machine Learning Porto Alegre](http://www.meetup.com/pt-BR/Machine-Learning-Porto-Alegre/) realizado no dia 27 de julho de 2016.

# Pré-requisitos
O código utilizado na apresentação foi feito em Python, logo para rodar é preciso tê-lo instalado na sua máquina.

# Requisitos
Para instalar as bibliotecas necessárias execute:
```
pip install -r requirements.txt
```

Ainda, esta apresentação utiliza os dados públicos do GitHub Archive estão disponíveis no [Google BigQuery](https://developers.google.com/bigquery/). E para conseguir rodar a apresentação na sua máquina, você deve seguir os passos descritos [AQUI](https://www.githubarchive.org/#bigquery), para ter acesso ao dataset.

# Rodar
Execute o seguinte comando:
```
jupyter notebook
```
Navegue até o arquivo **talk.ipynb** e abra-o. 

Para executar uma célula, clique nela e aperte `Shift` + `Enter`.

`IMPORTANTE:` a váriável **project_id** deve conter o seu project id. 

# Modo de visualização 
Para melhor apresentar o código utilizamos a extensão [RISE](https://github.com/damianavila/RISE) do Jupyter que possibilita mostrar cada célulo em formato de slide.