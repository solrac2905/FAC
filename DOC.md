# Comenzando 🚀
A continuación les agregamos las indicaciones para desplegar nuestra librería.

# Pre-requisitos 📋

requirements.txt
```
pip install -r requirements.txt
```
``` 
apex==0.1
appdirs @ file:///home/conda/feedstock_root/build_artifacts/appdirs_1603108395799/work
asttokens==2.2.1
attrs==22.2.0
awscli==1.27.70
awsio @ https://aws-s3-plugin.s3.us-west-2.amazonaws.com/binaries/0.0.1/1c3e69e/awsio-0.0.1-cp38-cp38-manylinux1_x86_64.whl
backcall==0.2.0
bcrypt==4.0.1
bokeh==2.4.3
boto3==1.26.70
botocore==1.29.70
brotlipy @ file:///home/conda/feedstock_root/build_artifacts/brotlipy_1666764652625/work
cached-property @ file:///home/conda/feedstock_root/build_artifacts/cached_property_1615209429212/work
certifi==2022.12.7
cffi @ file:///home/conda/feedstock_root/build_artifacts/cffi_1671179356964/work
charset-normalizer @ file:///home/conda/feedstock_root/build_artifacts/charset-normalizer_1661170624537/work
click==8.1.3
cloudpickle @ file:///home/conda/feedstock_root/build_artifacts/cloudpickle_1674202310934/work
cmake==3.18.2.post1
colorama==0.4.4
conda==22.11.1
conda-content-trust @ file:///home/conda/feedstock_root/build_artifacts/conda-content-trust_1621370699668/work
conda-package-handling @ file:///home/conda/feedstock_root/build_artifacts/conda-package-handling_1669907009957/work
conda_package_streaming @ file:///home/conda/feedstock_root/build_artifacts/conda-package-streaming_1669733752472/work
contextlib2==21.6.0
contourpy==1.0.7
cryptography @ file:///home/conda/feedstock_root/build_artifacts/cryptography-split_1675828607636/work
cycler==0.11.0
Cython @ file:///home/conda/feedstock_root/build_artifacts/cython_1673054071802/work
decorator==5.1.1
deepspeed @ https://aws-deepspeed-zero-2d-binaries.s3.us-west-2.amazonaws.com/r1.12.1/20221203-014851/b3d766ee27e7fa0e9b078665273a9550768445e7/deepspeed-0.6.1%2Bb3d766e-py3-none-any.whl
dgl==0.9.1.post1
dill==0.3.6
docutils==0.16
einops==0.6.0
executing==1.2.0
flash-attn==0.1
fonttools==4.38.0
fsspec==2023.1.0
gevent==22.10.2
google-pasta==0.2.0
greenlet==2.0.2
h5py @ file:///home/conda/feedstock_root/build_artifacts/h5py_1675704810568/work
hjson==3.1.0
horovod==0.24.3
idna @ file:///home/conda/feedstock_root/build_artifacts/idna_1663625384323/work
imageai==3.0.3
imageio==2.25.1
importlib-metadata==4.13.0
importlib-resources==5.10.2
iniconfig==2.0.0
inotify-simple==1.2.1
ipykernel==5.5.6
ipython==7.16.3
ipython-genutils==0.2.0
jedi==0.17.2
Jinja2==3.1.2
jmespath==1.0.1
joblib @ file:///home/conda/feedstock_root/build_artifacts/joblib_1663332044897/work
jsonpatch==1.32
jsonpointer==2.3
jupyter-client==6.1.5
jupyter-core==4.9.2
kiwisolver==1.4.4
libmambapy @ file:///home/conda/feedstock_root/build_artifacts/mamba-split_1671598321536/work/libmambapy
llvmlite==0.36.0
mamba @ file:///home/conda/feedstock_root/build_artifacts/mamba-split_1671598321536/work/mamba
MarkupSafe==2.1.2
matplotlib==3.7.0
matplotlib-inline==0.1.6
mock==4.0.3
mpi4py==3.1.3
multiprocess==0.70.14
networkx @ file:///home/conda/feedstock_root/build_artifacts/networkx_1673151334029/work
ninja==1.11.1
numba==0.53.1
numpy @ file:///home/conda/feedstock_root/build_artifacts/numpy_1668919078398/work
opencv-python==4.7.0.68
packaging @ file:///home/conda/feedstock_root/build_artifacts/packaging_1673482170163/work
pandas==1.5.3
paramiko==3.0.0
parso==0.7.1
pathos==0.3.0
pexpect==4.8.0
pickleshare==0.7.5
Pillow==9.4.0
plotly==5.13.0
pluggy @ file:///home/conda/feedstock_root/build_artifacts/pluggy_1667232663820/work
pooch @ file:///home/conda/feedstock_root/build_artifacts/pooch_1643032624649/work
portalocker==2.7.0
pox==0.3.2
ppft==1.7.6.6
prompt-toolkit==3.0.36
protobuf==3.20.2
protobuf3-to-dict==0.1.5
psutil @ file:///home/conda/feedstock_root/build_artifacts/psutil_1667885878918/work
ptyprocess==0.7.0
pure-eval==0.2.2
py==1.11.0
py-cpuinfo==9.0.0
pyarrow==11.0.0
pyasn1==0.4.8
pybind11==2.10.3
pycosat @ file:///home/conda/feedstock_root/build_artifacts/pycosat_1666834293299/work
pycparser @ file:///home/conda/feedstock_root/build_artifacts/pycparser_1636257122734/work
pyfunctional==1.4.3
Pygments==2.14.0
pyinstrument==3.4.2
pyinstrument-cext==0.2.4
PyNaCl==1.5.0
pyOpenSSL @ file:///home/conda/feedstock_root/build_artifacts/pyopenssl_1672659226110/work
pyparsing==3.0.9
PySocks @ file:///home/conda/feedstock_root/build_artifacts/pysocks_1661604839144/work
pytest==7.1.3
python-dateutil @ file:///home/conda/feedstock_root/build_artifacts/python-dateutil_1626286286081/work
pytz @ file:///home/conda/feedstock_root/build_artifacts/pytz_1673864280276/work
PyYAML==5.4.1
pyzmq==19.0.0
requests @ file:///home/conda/feedstock_root/build_artifacts/requests_1673863902341/work
retrying==1.3.4
rsa==4.7.2
ruamel.yaml @ file:///home/conda/feedstock_root/build_artifacts/ruamel.yaml_1666827402316/work
ruamel.yaml.clib @ file:///home/conda/feedstock_root/build_artifacts/ruamel.yaml.clib_1670412724006/work
s3fs==0.4.2
s3transfer==0.6.0
sagemaker==2.132.0
sagemaker-experiments==0.1.42
sagemaker-pytorch-training==2.7.0
sagemaker-training==4.4.5
schema==0.7.5
scikit-learn @ file:///home/conda/feedstock_root/build_artifacts/scikit-learn_1674598999530/work
scipy==1.10.0
seaborn==0.12.2
shap @ file:///home/conda/feedstock_root/build_artifacts/shap_1655716944211/work
six @ file:///home/conda/feedstock_root/build_artifacts/six_1620240208055/work
slicer @ file:///home/conda/feedstock_root/build_artifacts/slicer_1608146800664/work
smclarify==0.3
smdebug==1.0.24b20230214
smdebug-rulesconfig==1.0.1
smdistributed-dataparallel @ https://smdataparallel.s3.amazonaws.com/binary/pytorch/1.12.1/cu113/2022-12-05/smdistributed_dataparallel-1.6.0-cp38-cp38-linux_x86_64.whl
smdistributed-modelparallel @ https://sagemaker-distributed-model-parallel.s3.us-west-2.amazonaws.com/pytorch-1.12.1/build-artifacts/2022-12-08-21-34/smdistributed_modelparallel-1.13.0-cp38-cp38-linux_x86_64.whl
stack-data==0.6.2
tabulate==0.9.0
tenacity==8.2.1
threadpoolctl @ file:///home/conda/feedstock_root/build_artifacts/threadpoolctl_1643647933166/work
tomli==2.0.1
toolz @ file:///home/conda/feedstock_root/build_artifacts/toolz_1657485559105/work
torch @ https://aws-pytorch-unified-cicd-binaries.s3.us-west-2.amazonaws.com/r1.12.1_sm/20230106-042344/626f1a6ec58817e524705e0917dbab97c81b440e/torch-1.12.1%2Bcu113-cp38-cp38-linux_x86_64.whl
torchaudio @ https://download.pytorch.org/whl/cu113/torchaudio-0.12.1%2Bcu113-cp38-cp38-linux_x86_64.whl
torchdata @ https://download.pytorch.org/whl/test/torchdata-0.4.1-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
torchnet==0.0.4
torchvision @ https://download.pytorch.org/whl/cu113/torchvision-0.13.1%2Bcu113-cp38-cp38-linux_x86_64.whl
tornado==6.0.4
tqdm @ file:///home/conda/feedstock_root/build_artifacts/tqdm_1662214488106/work
traitlets==4.3.3
typing_extensions==4.4.0
urllib3 @ file:///home/conda/feedstock_root/build_artifacts/urllib3_1673452138552/work
visdom==0.2.4
wcwidth==0.2.6
websocket-client==1.5.1
Werkzeug==2.2.3
zipp @ file:///home/conda/feedstock_root/build_artifacts/zipp_1675982654259/work
zope.event==4.6
zope.interface==5.5.2
zstandard==0.19.0
```

# Construido con 🛠️
Herramientas utilizadas:
# 1. CREAR LIBRERÍA OPEN SOURCE EN PYTHON PARA ANÁLISIS Y RECUADROS DE OBJETOS IDENTIFICADOS

- Videos
Para el análisis de Videos -> Se utilizó el modelo de Red Neuronal Yolov3 que predice los cuadros delimitadores y las probabilidades de clase a partir de una imagen en una sola evaluación. Los modelos de YOLO pueden procesar más de 60 fotogramas por segundo, por lo que es una arquitectura excelente para detectar objetos en vídeos. El reconocimiento de objetos en imágenes ha sido una tarea muy dispendiosa y compleja y mas si se requiere ejecutar en tiempo real pero con los avances actuales, se ha utilizado la técnica YOLOv3 (You Only Look Once) Versión 3, el modelo más popular para la detección de objetos en tiempo real de última generación. Yolov3 (You Only Look Once v3) es un algoritmo de detección de objetos en imágenes y videos desarrollado por Joseph Redmon y Ali Farhadi. Se basa en una arquitectura de red neuronal convolucional profunda (CNN) y es conocido por su rapidez y precisión en la detección en tiempo real.

La idea principal detrás de Yolov3 es que en lugar de dividir la imagen en regiones y aplicar clasificadores de objetos en cada región, se trata de un enfoque de detección de objetos en una sola pasada. La red neuronal de Yolov3 se entrena para predecir directamente las cajas delimitadoras (bounding boxes) y las clases de los objetos en la imagen en una única operación, lo que la hace muy rápida.

Yolov3 utiliza una red neuronal convolucional llamada Darknet-53 como base, que es una red profunda con 53 capas convolucionales. La red Darknet-53 se utiliza para extraer características de la imagen y luego se aplican capas adicionales para predecir las cajas delimitadoras y las clases de los objetos.

Yolov3 es capaz de detectar y clasificar múltiples objetos en una imagen, incluso si están superpuestos o cercanos entre sí. También puede funcionar en tiempo real en videos, lo que la convierte en una herramienta popular para aplicaciones de detección de objetos en tiempo real, como la vigilancia por video, la conducción autónoma y la detección de objetos en imágenes en general.

Cabe destacar que Yolov3 es una versión anterior del algoritmo y, desde entonces, se han lanzado versiones más recientes como Yolov4 y Yolov5, que mejoran aún más la precisión y el rendimiento en la detección de objetos, para nuestra prueba utilizamos Versión 3.

https://developers.arcgis.com/python/guide/yolov3-object-detector/

![image](https://github.com/maribel-hernandez_adlover/README/assets/96451221/b8eef24d-2e00-4508-934d-6a2b66939305)

![image](https://github.com/maribel-hernandez_adlover/README/assets/96451221/f8b6684a-f2be-4740-b817-25d1264248b1)

![image](https://github.com/maribel-hernandez_adlover/README/assets/96451221/da2fa6f2-5005-433a-9013-d009efece3e2)


- Textos 
Para el análisis de Textos -> Se utilizó la librería Spacy, que es una de las librerías más utilizadas en el Lenguaje de Procesamiento de Lenguajes Naturales (NLPs) de Open Source. Proporciona una amplia gama de herramientas y funciones para realizar tareas de procesamiento del lenguaje natural, como el etiquetado de partes del discurso, el reconocimiento de entidades nombradas, el análisis de dependencias, el análisis de sentimientos, el desambiguación de palabras y la extracción de información, entre otros.
Spacy se destaca por su enfoque en la eficiencia y la velocidad de procesamiento. Está escrito en lenguaje de programación Python y ofrece modelos preentrenados para varios idiomas, lo que facilita su uso en una variedad de aplicaciones. Además, permite entrenar modelos personalizados en función de los datos y requisitos específicos de un proyecto.

La librería también incluye una interfaz de línea de comandos y una API que facilita su integración en aplicaciones y flujos de trabajo existentes. Spacy se ha convertido en una herramienta popular en la comunidad de procesamiento del lenguaje natural debido a su facilidad de uso, su rendimiento y su enfoque en la producción de resultados de alta calidad.

Contribuyendo 🖇️
Por favor lee el CONTRIBUTING.md para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

# Versionado 📌
V0-0

# 2. IDENTIFICACIÓN DE ENTIDADES EN NOTICIAS
El archivo README describe el uso de la librería
Al seguir las instrucciones del README es claro cómo usar la librería

La librería se puede importar
El README explica las estrategias usadas para resolver el reto

la librería debe incluir un archivo README que explique el uso de la librería y documentación detallada de los métodos y clases en el código. El README debe tener instrucciones claras sobre la creación y uso (i.e., import) de la librería a partir del código fuente en el repositorio, es decir, se deben explicar las técnicas usadas, pipeline, etc. En el README se debe describir detalladamente cómo se resolvió cada objetivo, es decir, se deben explicar las técnicas usadas, pipeline, etc.

Las funciones deben contar con comentarios “inline”, es decir, comentarios/documentación en el código que explique la estrategia usada. Esta es una guía de ejemplo sobre documentación de código en python: https://realpython.com/documenting-p

# Autores ✒️
- DS - Carlos Eduardo López Ramos
- DE - Jorge Andres Camacho Ramírez
- DE - Diego Alejandro Buitrago Avila
- DE - Maribel Hernández Giraldo

ADL - Augusta
También puedes mirar la lista de todos los contribuyentes quíenes han participado en este proyecto.

# Licencia 📄
Esta librería es Open Source
