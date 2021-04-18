# MLBolsa

## Crear Entorno Virtual

Para poder utilizar los notebooks primero recomendamos armar un entorno virtual con Python 3 utilizando alguna de las siguientes herramientas:

- [Conda](https://docs.conda.io/en/latest/)
- [Virtualenv](https://virtualenv.pypa.io/en/latest/)

> Ayuda: [Entornos Virtuales en Python y Anaconda](https://unipython.com/entornos-virtuales-en-python-y-anaconda/)

## Instalar requerimientos

Luego de acivar el entorno virtual, correr el siguiente comando según lo hayas creado con conda o con virtualenv:
```bash
# En caso de conda
conda install -c anaconda pandas-datareader jupyterlab

# En caso de pip
pip install pandas-datareader jupyterlab
```

## Correr Jupyter Lab

```bash
jupyter-lab DatosMLBolsa.ipynb
```
