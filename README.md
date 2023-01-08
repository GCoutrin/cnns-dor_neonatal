# cnns-dor_neonatal

Este repositório contém os códigos elaborados para a dissertação "Redes Neurais Convolucionais para Avaliação de Dor Neonatal em Imagens de Face: Uma Análise Quantitativa e Qualitativa", ainda em desenvolvimento.

O objetivo geral desta dissertação é realizar uma comparação de diferentes modelos de Redes Neurais Convolucionais na classificação automática de expressões faciais de dor em recém-nascidos, considerando resultados quantitativos (métricas de desempenho) e qualitativos (mapas de ativação de classe gerados pelo método Grad-CAM).

Até o momento, o repositório possui 4 arquivos .ipynb:

* **Prepara_imagens.ipynb**: este notebook apresenta um conjunto de códigos desenvolvidos para o pré-processamento e organização da banco de imagens utilizado;
* **Treinamento.ipynb**: este notebook apresenta a rotina de treinamento e validação aplicada à 5 CNNs distintas, considerando a tarefa do reconhecimento de expressões facias de dor em recém-nascidos;
* **ANOVA.ipynb**: este notebook apresenta a aplicação da Análise de Variância (ANOVA) para a comparação quantitativa do desempenho de 5 CNNs;
* **GradCAM.ipynb**: este notebook apresenta a aplicação do método Gradient-weighted Class Activation Mapping (Grad-CAM) para interpretação das classificações realizadas por 5 CNNs distintas.
