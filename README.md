# Odometria

Códigos da área de Odometria.

Gestão de Conhecimento sobre FFT:
- Programa em Python feito no Colab sobre FFT, filtros FFT e Análise de Resultados ([Link](https://colab.research.google.com/drive/1QgjrMzpZ5-_IPdDeu_B1iAMUFPIRCFMa?usp=sharing)):
    - Explicação do código:
      1) Leitura do dataset
      2) Transformação dos dados do domínio do tempo para o domínio da frequência por meio da FFT
      3) Por fim, Plot de gráficos, tanto os gráficos no domínio do tempo quanto os gráficos em que eu comparo as densidades espectrais (áreas sob a curva da FFT de cada caso experimental)
    - Observações sobre o código:
        - Foram precisas algumas adaptações, principalmente na variação de tempo (delta_t) existente entre um dado e o seguinte. O delta_t varia para cada um dos experimentos e entre cada dado também
        - Para facilitar, foi atribuído um valor aproximado para essa variação
        - Vale ressaltar essa informação pois o delta_t é uma variável importante para a transformação do domínio do tempo para o domínio da frequência
- Vídeos para referencial teórico sobre FFT:
    - https://youtu.be/s2K1JfNR7Sc?si=yCf7i2vZBml5ThgW
    - https://youtu.be/1-i4byj3MqI?si=CD1mIfa52hOPq3Vo
