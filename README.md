# Node Classification

Prever as classes ou rótulos dos nós. Pode ser utilizado para detectar entidades fraudulentas na rede em segurança cibernética, assim pode ser um problema de classificação de nós.

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

Após isso, vamos criar o modelo de classificação de nós com o notebook:

[processing.ipynb](https://github.com/charlesluizmendes/GNN/blob/feature/nodeClassification/src/processing.ipynb)

### Inferência

Agora podemos fazer a inferência do modelo gerado na etapa anterior, basta executar o notebook:

[inference.ipynb](https://github.com/charlesluizmendes/GNN/blob/feature/nodeClassification/src/inference.ipynb)