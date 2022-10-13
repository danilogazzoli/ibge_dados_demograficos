# ibge_dados_demograficos
Raspagem dos dados da página do IBGE, passando como parâmetro a cidade e UF

rodar no terminal:

```bash
sudo apt install virtualenv

virtualenv --python=python3.9 .ibge

source .ibge/bin/activate

pip install --upgrade jupyterhub

pip install --upgrade --user nbconvert

pip install -r requirements.txt
```


abrir o jupyter com o comando (na pasta do projeto):

```bash
jupyter notebook .
```
