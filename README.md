# Face ID
Este projeto de iniciação científica objetiva investigar abordagens baseadas em Arquiteturas Profundas para extração automática das características e análise de padrões de faces considerando utilizar apenas uma face como exemplo de treinamento.
Onde se resume em uma rede convolucional siamêsa baseada na arquitetura SqueezeNet com perda contrastiva

**Projeto referência:** [How I implemented iPhone X’s FaceID using Deep Learning in Python](https://towardsdatascience.com/how-i-implemented-iphone-xs-faceid-using-deep-learning-in-python-d5dbaa128e1d)

**Material auxiliar:** [Lecture Collection | Convolutional Neural Networks for Visual Recognition (Spring 2017)](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)


**RGB-D Face Dataset:** [Banco de dados usado no projeto](https://drive.google.com/drive/folders/1cB_dm90jsqq5pUqlgSAB5juCecpoG-4o?usp=sharing)

**Modelo Haarcascade:** [Modelo usado no reconhecimento facial do OpenCV](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_alt.xml)


**Rodar o projeto:**
- sudo apt-get update
- sudo apt-get install python3.6
- sudo apt-get install python3-pip

- pip3 install -r requirements.txt

- python3 faceId.py
