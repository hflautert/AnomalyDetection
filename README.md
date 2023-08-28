# AnomalyDetection

Neste repositório é apresentado um modelo de detecção de anomalias em redes IoT. 

This repository presents an anomaly detection model in IoT networks.

### Apresentação do Modelo:
https://github.com/hflautert/AnomalyDetection/blob/main/ModeloHMM.ipynb

### Funções:
[https://gist.github.com/hflautert/c0d5dee869cb369a912de6b8c02d457e](https://gist.github.com/hflautert/c0d5dee869cb369a912de6b8c02d457e)

### Resultados e Configurações Gerais:

| Tempo  | Precisão | Delta G | k | Taxa Mínima | Inicialização (m) |
| ------ | -------- | ------- | -------------- | ------------|-------------------|
| 1 Minuto          |	100,00% |	1,10 |	10	| 75,38 |	10,00 |
| 10 Segundos       |	97,67%  |	1,10 |	41	| 15,00 |	6,77  |
| 1 Segundo         |	90%     |	1,05 |	300 |	7,50  |	4,99  |
| 500 Milissegundos |	88,89%  |	1,04 |	448 |	3,68  |	3,73  |
| 100 Milissegundos |	89,66%  |	1,04 | 2213 |	1,13  |	3,69  | 
