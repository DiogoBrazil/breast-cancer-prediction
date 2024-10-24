
# Projeto de Classificação de Câncer de Mama com Redes Neurais

## Descrição
Este projeto tem como objetivo a **classificação de câncer de mama** através de imagens de mamografia. 
Serão desenvolvidas **duas redes neurais** utilizando **TensorFlow** e **YOLOv8** para apoiar o diagnóstico médico.

- **Primeira Rede Neural:** Classificará se uma imagem possui câncer ou é normal.
- **Segunda Rede Neural:** Classificará entre as classes: **normal**, **benigno** e **maligno**.

## Objetivo
O projeto visa **auxiliar os médicos das unidades de saúde** da cidade de **Ariquemes-RO** no diagnóstico de câncer de mama, 
fornecendo **maior precisão e diagnóstico precoce**. O diagnóstico precoce é essencial para aumentar as chances de sucesso no tratamento.

## Ferramentas e Tecnologias Utilizadas
- TensorFlow
- YOLOv8
- Python
- OpenCV
- Jupyter Notebook

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/DiogoBrazil/nome-do-projeto.git
   ```
2. Crie um ambiente virtual com Conda:
   ```bash
   conda create --name cancer_mama python=3.12
   conda activate cancer_mama
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install tensorflow opencv-python ultralytics
   ```
4. Execute os notebooks para treinar e validar as redes neurais.

## Autor
Projeto desenvolvido por [DiogoBrazil](https://github.com/DiogoBrazil).
