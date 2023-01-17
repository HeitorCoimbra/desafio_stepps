# desafio_stepps
Desafio de Computer Vision p/ a Stepps

## Desafio Opcional: Contagem e Tracking de Mamões

Nessa parte mais elaborada do desafio, construí duas soluções. 

A primeira, e mais eficiente, utiliza da implementação original do algoritmo SORT para realizar o tracking assistido das detecções da YOLOv7. 

A segunda versão é bem mais simples e utiliza um algoritmo de tracking implementado quase todo por mim e utiliza a lógica de filtros de kalman utilizando uma regressão linear de posição para prever a próxima posição de cada objeto e associar eles por proximidade a cada frame.

De longe, a versão que utiliza SORT funciona muito melhor do que a versão de filtros de Kalman.

Não utilizei a informação da linha amarela, nem os timestamps informados no desafio. Isso se deu por falta de tempo, dado que durante os primeiros 6 dias do desafio eu estava fora de casa e implementei o código todo no Google Colab.

### Execução

Para rodar o código, basta rodar o arquivo tracking.py para rodar a contagem simples e o arquivo detect_or_track.py para rodar a detecção com SORT de acordo com os parametros necessarios.

### Vídeos de contagem

Os vídeos não couberam no git, portanto se encontram aqui : https://drive.google.com/drive/folders/1MXRMMAw1oZPKOXUiayVPLmAnCNpaNnWi?usp=sharing
