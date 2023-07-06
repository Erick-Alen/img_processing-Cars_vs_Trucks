# Algoritmo de classificação de imagens - carros e caminhonetes/SUVs

## Equipe
Erick Alen Ricioli - [Vídeo Apresentação](https://youtu.be/a7TdXLZHLQY)
## Dataset
O dataset [Car or Truck?](https://www.kaggle.com/datasets/ryanholbrook/car-or-truck) do kaggle foi escolhido através do material de apoio fornecido.

## Classificador e acurácia

Este é o projeto foi realizado a partir da rede neural convolucional [AlexNet](https://medium.com/analytics-vidhya/concept-of-alexnet-convolutional-neural-network-6e73b4f9ee30).

O algoritmo foi projetado para classificar imagens entre carros ou caminhonetes, contendo em seu dataset cerca de 5 mil imagens para cada classe. Sua limitação está no número de classes que o mesmo identificará, pois ele é binário, identificando dois tipos de imagens, carros e caminhonetes/SUVs.

Sua acurácia ficou em torno de 88% a 90%, segundo os treinamentos realizados

Material usado neste código:

- [Jupyter notebook](https://jupyter.org/install): Usado para mostrar o desenvolvimento do código em blocos.
- [Scikit-Learn](https://scikit-learn.org/): Usado para mostrar a matriz de confusão e classificação.
- [Matplotlib](https://matplotlib.org/): biblioteca usada para construir os gráficos dos resultados do modelo;
- [Keras](https://keras.io/): API construída em cima do Tensorflow para aprendizado profundo(Deep Learning);
- [Tensorflow](https://www.tensorflow.org/?hl=pt-br): biblioteca usada para aprendizado de máquina;

## Instalação

É necessário possuir o python instalado ([link](https://www.python.org/downloads/)), e marcar a opção de "adicionar nas variáveis de ambiente ao instalar.

Para checar se o Python foi instalado corretamente, digite em seu terminal o seguinte comando:

```
pip --version
```

Para instalar as bibliotecas da aplicação basta rodar o seguinte comando na pasta do projeto:

```
pip install matplotlib scikit-learn tensorflow jupyterlab notebook
```

## Execução do notebook em ambiente local

Para executar o jupyter notebook no seu ambiente local, basta entrar no diretório que contém o arquivo notebook e o dataset e execute no seu terminal de comando:

```
jupyter notebook
```
Com o ambiente e as extensões já instalados, basta entrar no arquivo `Cars_vs_Trucks.ipynb` e colocar nas variáveis `train_dir` e `validation_dir` os diretórios das pastas de treino e validação, respectivamente. Após isso, basta ir até a aba Células(Cells) e clicar na opção `executar tudo`
