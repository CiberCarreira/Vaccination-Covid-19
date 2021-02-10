# Vaccination-Covid-19
Esse trabalho apresenta uma forma dinâmica de visualizar os números de vacinação da covid-19 pelo mundo.

O objetivo desse código é apenas visualizar de forma dinâmica o crescimento do número de vacinações pelo mundo.

Os pacotes e requisitos necessários vão ser:

- instalação do ffmpeg - Para visualização do vídeo gerao.
- Pacote pandas
- Pacote bar_chart_race

Devido ao conjunto de dados possui muitos valores faltantes, foi feito um processo de imputação de dados, primeiro substituindo todos os valroes NaN por 0 e depois substituindo os zeros pelo seu maior valor que antecedesse, sendo que on de os valores antecessores já eram zeros, o valor permaneceu igual.
