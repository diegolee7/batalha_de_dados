# Gestão Inteligente da Saúde Pública
O GISP é um sistema que facilita a tomada de decisão da gestão de saúde pública.
Dados abertos são cruzados com dados geolocalizados das Unidades de Saúde, que são usados para alimentação de uma ferramenta de visualização, e para um modelo de Machine Learning, responsável por predizer a quantidade de atendimentos por unidade de saúde em um determinado espaço de tempo.

# Dashboard:
Visualização de dados de atendimentos em unidades públicas de saúde na região metropolitana de Curitiba. Auxilia a gestão da saúde na tomada de decisão.

# Modelo Preditivo
Entrada:
* Latitude Da Unidade de Saúde
* Longitude Da Unidade de Saúde
* Temperatura Máxima do Dia
* Temperatura Mínima do Dia
* Dia da Semana
* Média do Número de Pessoas Atendidas nos Últimos 7 Dias na Unidade de Saúde com as Seguinte Condições:
	* Coleta de Lixo de Má Qualidade
	* Habitacao de Má Qualidade
	* Sem Energia
	* Sem Carro

Predição:
* Número de Atendimentos