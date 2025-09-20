# GNN (Graph Neural Network)

Prevê a existência de potenciais ligações (arestas) entre nós.  Pode ser utilizado para um serviço de rede social sugere possíveis conexões de amigos com base em dados de rede.

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

Após isso, vamos criar o modelo de previsão de Links com o notebook:

[processing.ipynb](https://github.com/charlesluizmendes/GNN/blob/main/src/processing.ipynb)

### Inferência

Agora podemos fazer a inferência do modelo gerado na etapa anterior, basta executar o notebook:

[inference.ipynb](https://github.com/charlesluizmendes/GNN/blob/main/src/inference.ipynb)