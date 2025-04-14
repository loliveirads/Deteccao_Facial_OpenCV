# Deteccao_Facial_OpenCV

Projeto da Atividade 1 do desafio PBL TSCO 2º Ano da FIAP.

Este projeto demonstra a detecção facial usando OpenCV e Haar Cascades em imagens de diferentes pessoas. O objetivo é validar a viabilidade de um sistema automatizado de retirada de mercadorias com reconhecimento facial.

## Requisitos

- Python 3.11  
- Poetry instalado  
- VSCode (opcional)  
- Jupyter Notebook (instalado via Poetry)  

## Passo a passo para rodar o projeto

1. Clone o repositório  
git clone git@github.com:loliveirads/Deteccao_Facial_OpenCV.git  
cd Deteccao_Facial_OpenCV

2. Inicialize o projeto com o Poetry  
poetry init --no-interaction  
poetry add opencv-python matplotlib  
poetry add notebook ipykernel --dev

3. Ative o ambiente virtual  
poetry shell

4. Crie o kernel Jupyter  
python -m ipykernel install --user --name cap06-opencv --display-name "Python (CAP_06 OpenCV)"

5. Organize as imagens dentro da pasta `imagens/` com a seguinte estrutura:  
imagens/  
├── pessoa_1/  
│   └── img_01.jpg ... img_05.jpg  
├── pessoa_2/  
│   └── img_01.jpg ... img_05.jpg  

*Observação: a imagem `img_05.jpg` de cada pasta será usada para teste de detecção.*

6. Execute o notebook  
jupyter notebook  

Ou abra o arquivo `Deteccao_Facial_OpenCV.ipynb` no VSCode e selecione o kernel: Python (CAP_06 OpenCV)


