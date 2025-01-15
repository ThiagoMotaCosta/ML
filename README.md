# ML
Machine Learning

Passo a Passo

Criação do recurso de Machine Learning no MarketPlace e depois direcionamento ao Estúdio.

No Estúdio, seguir o passo a passo que está no endereço WEB:
https://microsoftlearning.github.io/AI-900-AIFundamentals.pt-BR/Instructions/02-module-02.html

Nesse caso, uma diferença na fonte de dados via Web que apresentou erro de Encoding (assim, baixamos o arquivo Zipado e subimos o csv que constava )

No estúdio do Azure Machine Learning, veja a página ML Automatizado (em Criação).

Crie um novo trabalho de ML automatizado com as seguintes configurações, usando Avançar conforme necessário para avançar dentro da interface do usuário:

Configurações básicas:

Nome do trabalho: mslearn-bike-automl
Nome do novo experimento: mslearn-bike-rental
Descrição: machine learning automatizado para previsão de aluguel de bicicletas
Marcas: nenhuma
Tipo de tarefa e dados:

Selecionar tipo de tarefa: regressão
Selecionar conjunto de dados: crie um novo conjunto de dados com as seguintes configurações:
Tipo de dados:
Nome: bike-rentals
Descrição: dados históricos de aluguel de bicicletas
Tipo: tabular
Fonte de dados:

Nesse passo, ir em arquivo local e selecionar o csv daily-bike-share.csv

após a validação, colocar os dados separados por virgula e em UTF-8

Uma vez configurado o dado, selecionar em regressão e avançar

realizar todas as configurações necessárias:
1 - Coluna Destino: Rentals (Integer)
2 - com tipo de RandomForest e Light
3 -realizar as configurções de limite.
4 - Tipo de validação com dados de treinamento

Posteriormente examinar e uma vez concluído com sucesso, verificar as métricas no modelo em Tarefas(Job)
