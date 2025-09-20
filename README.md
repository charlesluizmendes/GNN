# GNN (Graph Neural Network)

Rede Neural de Grafos utilizando PyTorch e PyTorch Geometric.

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

### Processamento

Após isso, vamos criar o modelo treinando para análise de sentimentos com o notebook:

[processing.ipynb](https://github.com/charlesluizmendes/GNN/blob/main/src/processing.ipynb)

### Inferência

Agora podemos fazer a inferência do modelo gerado na etapa anterior, basta executar o notebook:

[inference.ipynb](https://github.com/charlesluizmendes/GNN/blob/main/src/inference.ipynb)