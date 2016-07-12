a) conferir se os seguintes arquivos estão na pasta atual
  	* arface-solver.prototxt
	* arface-deploy-com-camada-dados.prototxt
	* treino-base-total.txt
	* teste.txt

b) conferir a localização do arquivo com o modelo da rede pré-treinada (VGG_FACE.caffemodel). se necessário mudar a localização no arquivo arface-executar.bin

c) conferir o caminho das imagens definido nos arquivos teste.txt e treino-base-total.txt

d) conferir os demais arquivos necessários para a execução da Caffe.

e) Para executar, utilize o script arface-executar.bin
  exemplo: sh arface-executar.bin

Obs: Caso deseje testar com outra colecao de treino,
     basta mudar o nome da base de dados definida no arquivo arface-deploy-com-camada-dados.prototxt 
     para o nome da colecao desejada (treino-b2.txt , treino-b4.txt, treino-b8.txt)

     Os arquivos info... mostram os resultados dos experimentos em cada dataset.

