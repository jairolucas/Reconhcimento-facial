a) conferir se os seguintes arquivos est�o na pasta atual
  	* arface-solver.prototxt
	* arface-deploy-com-camada-dados.prototxt
	* treino-base-total.txt
	* teste.txt

b) conferir a localiza��o do arquivo com o modelo da rede pr�-treinada (VGG_FACE.caffemodel). se necess�rio mudar a localiza��o no arquivo arface-executar.bin

c) conferir o caminho das imagens definido nos arquivos teste.txt e treino-base-total.txt

d) conferir os demais arquivos necess�rios para a execu��o da Caffe.

e) Para executar, utilize o script arface-executar.bin
  exemplo: sh arface-executar.bin

Obs: Caso deseje testar com outra colecao de treino,
     basta mudar o nome da base de dados definida no arquivo arface-deploy-com-camada-dados.prototxt 
     para o nome da colecao desejada (treino-b2.txt , treino-b4.txt, treino-b8.txt)

     Os arquivos info... mostram os resultados dos experimentos em cada dataset.

