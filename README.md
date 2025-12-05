# PD-validacao-clusterizacao

### Clusterização de modelos de carros elétricos

Os carros elétricos clusterizados de forma interativa podem ser visualizados em: https://roriblim.github.io/PD-validacao-clusterizacao/src/tsne_clusters.html

#### Procedimentos utilizados para preparar o ambiente

1. Foi utilizado o Anaconda 25.5.1 para gerenciar o ambiente virtual.

2. Para ativar o Anaconda, foi feito:
```
source ~/anaconda3/bin/activate
```

3. Para criar o ambiente virtual, com o Anaconda ativado, foi feito:
```
conda create --name PD_clusterizacao python=3.12 --no-default-packages -y
```

4. Para ativar o ambiente virtual, com o Anaconda ativado, foi feito:
```
conda activate PD_clusterizacao
```

5. Com o requirements.in, posso gerar o requirements.txt com as dependências pinadas. Para isso, foi instalado o pip-tools e realizado o pip-compile:
```
python -m pip install pip-tools
pip-compile
```

6. Por fim, para instalar as dependências do requirements.txt:
```
pip install -r requirements.txt
```

