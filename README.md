# Deteccao_Facial_OpenCV

Projeto da Atividade 1 do desafio PBL TSCO 2º Ano da FIAP.

O objetivo é demonstrar a viabilidade de um sistema automatizado de retirada de mercadorias utilizando detecção facial com OpenCV (Haar Cascades).

## Requisitos

- Python 3.11  
- Poetry instalado  
- Jupyter Notebook  
- VSCode (opcional)

## Passo a passo

### 1. Clonar o repositório

```bash
git clone git@github.com:loliveirads/Deteccao_Facial_OpenCV.git
cd Deteccao_Facial_OpenCV
```

### 2. Inicializar o ambiente com Poetry

```bash
poetry init --no-interaction
poetry add opencv-python matplotlib
poetry add notebook ipykernel --dev
```

### 3. Ativar o ambiente virtual

```bash
poetry shell
```

### 4. Criar o kernel Jupyter

```bash
python -m ipykernel install --user --name cap06-opencv --display-name "Python (CAP_06 OpenCV)"
```

### 5. Estrutura de pastas esperada

```
imagens/
├── pessoa_1/
│   ├── img_01.jpg
│   ├── img_02.jpg
│   ├── img_03.jpg
│   ├── img_04.jpg
│   └── img_05.jpg
├── pessoa_2/
│   └── ...
```

A imagem `img_05.jpg` de cada pessoa será usada para teste de detecção.

### 6. Executar o notebook

```bash
jupyter notebook
```

Ou abra o arquivo `Deteccao_Facial_OpenCV.ipynb` no VSCode e selecione o kernel: **Python (CAP_06 OpenCV)**




