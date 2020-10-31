# Projeto

Projeto de reconhecimento de faces em imagens, foi desenvolvido em python utilizando principalmente as bibliotecas OpenCV para imagens e scikit learn para separa��o de amostras e medi��o da acur�cia alcan�ada.

# Como utilizar

Baixar o script face_detection.ipynb e o arquivo ORL.rar disponibilizados. Descompactar o arquivo .rar no mesmo diret�rio onde se enconta o notebook. 

Arquivos com a extens�o ipynb podem ser abertos no Google Colab ou Jupyter Notebook.

A principal biblioteca utilizada � opencv-contrib-python, para instala��o da mesma utilizar o comando:
```python
!python -m pip install --user opencv-contrib-python
```

# Resultados

Execu��o utilizando de 10 a 20 componentes principais (PCA).
```python
PCA number: 10, accuracy score: 95.12%
PCA number: 11, accuracy score: 95.12%
PCA number: 12, accuracy score: 95.12%
PCA number: 13, accuracy score: 95.93%
PCA number: 14, accuracy score: 95.12%
PCA number: 15, accuracy score: 95.93%
PCA number: 16, accuracy score: 95.93%
PCA number: 17, accuracy score: 95.12%
PCA number: 18, accuracy score: 95.12%
PCA number: 19, accuracy score: 95.12%
PCA number: 20, accuracy score: 95.93%
```