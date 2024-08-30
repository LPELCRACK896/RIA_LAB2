# UVG - RIA - SHAP Visualization Lab with TensorFlow

**Autor**: Luis Pedro Gonzalez Aldana

Basado en https://jmerida30.github.io/OBJRECLAB/


## Python

Utilizando `Python 3.12.5` en Windows. 

## Setup

Uso el archivo `requirements.txt` con el siguiente contenido: 
```txt
numpy
pandas
torch
torchvision
scikit-learn
shap
scipy
matplotlib
transformers
nltk
tensorflow
```
Sin indicar las versiones porque al hacerlo inicialmente no encontró el paqeute `distutils`, posiblemente porque se usó otra versión de python.

Ejecuto (teniendo activo el virtualenv): 
```shell
pip install -r requirements.txt
```
Cuando se instala todo vuelvo a guardar las dependencias con sus respectivas versiones en requirements.txt.

```shell
pip freeze > requirements.txt
```

Este fue el resultado 

```txt
absl-py==2.1.0
astunparse==1.6.3
certifi==2024.8.30
charset-normalizer==3.3.2
click==8.1.7
cloudpickle==3.0.0
colorama==0.4.6
contourpy==1.3.0
cycler==0.12.1
filelock==3.15.4
flatbuffers==24.3.25
fonttools==4.53.1
fsspec==2024.6.1
gast==0.6.0
google-pasta==0.2.0
grpcio==1.66.1
h5py==3.11.0
huggingface-hub==0.24.6
idna==3.8
Jinja2==3.1.4
joblib==1.4.2
keras==3.5.0
kiwisolver==1.4.5
libclang==18.1.1
llvmlite==0.43.0
Markdown==3.7
markdown-it-py==3.0.0
MarkupSafe==2.1.5
matplotlib==3.9.2
mdurl==0.1.2
ml-dtypes==0.4.0
mpmath==1.3.0
namex==0.0.8
networkx==3.3
nltk==3.9.1
numba==0.60.0
numpy==1.26.4
opt-einsum==3.3.0
optree==0.12.1
packaging==24.1
pandas==2.2.2
pillow==10.4.0
protobuf==4.25.4
Pygments==2.18.0
pyparsing==3.1.4
python-dateutil==2.9.0.post0
pytz==2024.1
PyYAML==6.0.2
regex==2024.7.24
requests==2.32.3
rich==13.8.0
safetensors==0.4.4
scikit-learn==1.5.1
scipy==1.14.1
setuptools==74.0.0
shap==0.46.0
six==1.16.0
slicer==0.0.8
sympy==1.13.2
tensorboard==2.17.1
tensorboard-data-server==0.7.2
tensorflow==2.17.0
tensorflow-intel==2.17.0
termcolor==2.4.0
threadpoolctl==3.5.0
tokenizers==0.19.1
torch==2.4.0
torchvision==0.19.0
tqdm==4.66.5
transformers==4.44.2
typing_extensions==4.12.2
tzdata==2024.1
urllib3==2.2.2
Werkzeug==3.0.4
wheel==0.44.0
wrapt==1.16.0
```

Para el uso de esto en un notebook instalo adicionalmente `ipykernel` y `notebook`. 

```shell
pip install ipykernel notebook

```

Parece que también faltan otras: 

```shell
pip install ipywidgets 
```

```shell
pip freeze > requirements.txt
```

