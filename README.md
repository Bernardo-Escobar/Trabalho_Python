# Trabalho Python: Morfologia
# Alunos: Bernardo Victoria Escobar Silva e Gabriel Santos Bortoloci

O código que usamos para fazer a atividade foi o de morfologia. Esse código utiliza algumas das principais funções morfológicas (erosão, dilatação, gradiente, abertura e fechamento). Operações morfológicas, são funções/operações para o processamento de imagens com base em formas.

O código utiliza um kernel para fazer as funções funcionarem. Um kernel é uma matriz que vai servir para mudar a imagem. Para fazer a alteração da imagem, o kernel tem um ponto de ancoragem, e é ele quem administra como os pixels da imagem serão alterados. Ele funciona com base na convolução, onde isso é uma operação matemática que permite alterar partes específicas de uma imagem.

Como já citei anteriormente, vou explicar o que cada uma das funções utilizadas fazem:

Erosão (erosion):
A erosão é uma operação morfológica que é usada para encolher ou afinar uma parte de uma imagem. Ela funciona removendo pixels da borda dos objetos, o que resulta na diminuição do tamanho desses objetos ou até mesmo na sua completa remoção, dependendo do tamanho do elemento utilizado. A erosão é útil para remoção de ruídos, separação de objetos conectados e simplificação da forma dos objetos.

Dilatação (dilation):
A dilatação é o oposto da erosão. Ela é usada para expandir ou dilatar uma parte de uma imagem. A dilatação funciona adicionando pixels à borda dos objetos, o que resulta no aumento do tamanho desses objetos. É útil para preencher lacunas, unir objetos próximos e melhorar a conectividade de componentes.

Gradiente (gradient):
O gradiente morfológico é uma função que calcula a diferença entre a dilatação e a erosão de uma imagem. Ele destaca as bordas entre objetos na imagem. O que pode ser útil para detecção de bordas.

Abertura (opening):
A abertura é uma combinação da erosão seguida da dilatação. Ela é usada para remover pequenos objetos, suavizar bordas e preencher pequenas lacunas em objetos maiores. A abertura é útil para limpar imagens, reduzir ruídos e melhorar a qualidade de pontos específicos da imagem.

Fechamento (closing):
O fechamento é o oposto da abertura e é uma combinação da dilatação seguida da erosão. Ele é usado para preencher lacunas em objetos, suavizar bordas e unir objetos próximos. O fechamento é útil para preencher buracos e restaurar a forma original dos objetos.
