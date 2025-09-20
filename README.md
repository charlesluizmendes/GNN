# Edge Classification

Classifica a carga (baixa, média ou alta) nas conexões de rede. Pode ser utilizado em sistemas de redes ad hoc para identificar riscos de congestionamento e aumento de latência quando múltiplos nós comunicam simultaneamente, auxiliando no balanceamento de tráfego e na prevenção de falhas.

## Ambiente 

### Pacotes

Podemos instalar as dependências do projeto através do comando abaixo:

```
$ pip install -r requirements.txt
```

Ou manualmente através dos seguintes comandos:

```
pip install torch
pip install torch-geometric
```

* Se possuir recursos de CUDA:

```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

## Execução

### Dataset

Primeiramente vamos criar o dataset com notebook:

[dataset.ipynb](https://github.com/charlesluizmendes/GNN/blob/feature/edgeClassification/src/dataset.ipynb)

### Processamento

Após isso, vamos criar o modelo de previsão de Links com o notebook:

[processing.ipynb](https://github.com/charlesluizmendes/GNN/blob/feature/edgeClassification/src/processing.ipynb)

### Inferência

Agora podemos fazer a inferência do modelo gerado na etapa anterior, basta executar o notebook:

[inference.ipynb](https://github.com/charlesluizmendes/GNN/blob/feature/edgeClassification/src/inference.ipynb)