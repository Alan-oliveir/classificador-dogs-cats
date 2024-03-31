<a target="_blank" href="https://colab.research.google.com/github/Alan-oliveir/classificador-dogs-cats/blob/main/transfer_learning_dogs_cats.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Classificador de cães e gatos

Vamos classificar imagens de cães e gatos usando transferência de aprendizado de uma rede pré-treinada.
Um modelo pré-treinado é uma rede neural que foi previamente treinada em um extenso conjunto de dados, geralmente para realizar uma tarefa de classificação de imagens em grande escala.
O modelo base foi construído utilizando o MobileNet V2 desenvolvido pelo Google. Este modelo é pré-treinado no conjunto de dados ImageNet, composto por 1,4 milhão de imagens distribuídas em 1.000 classes distintas.
ImageNet é um conjunto de dados de referência para pesquisas, abrangendo uma vasta gama de categorias, desde frutas como jaca até itens como seringas. 
Essa base de conhecimento será fundamental para classificar cães e gatos em nosso conjunto de dados específico.

___
**Observação**: Este projeto foi feito para a Formação Machine Learning Specialist da DIO, no módulo Programação para Machine Learning seguindo um tutorial do Tensorflow para transfer learning.  
