# IA para Tradução de Libras - Projeto de TCC

[![Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)](#)
[![Linguagem: Python](https://img.shields.io/badge/Linguagem-Python-blue)](#)
[![Licença: MIT](https://img.shields.io/badge/License-MIT-green)](#)

## 📌 Sobre o Projeto
Este repositório contém o código-fonte e a documentação do projeto de pesquisa desenvolvido para o Trabalho de Conclusão de Curso (TCC) em Ciência da Computação. 

O objetivo central desta pesquisa é desenvolver e validar um modelo de **Inteligência Artificial (Visão Computacional)** capaz de reconhecer e traduzir os gestos da Língua Brasileira de Sinais (Libras) em tempo real. A solução visa atuar como uma ponte tecnológica para promover a acessibilidade e a inclusão social da comunidade surda.

## ⚙️ Funcionalidades e Escopo
- Captura e processamento de imagens/vídeos em tempo real.
- Extração de características espaciais e mapeamento de pontos de articulação (mãos, face e postura).
- Classificação de gestos utilizando redes neurais artificiais.
- Saída de texto iterativa correspondente ao sinal identificado.

## 🛠️ Stack Tecnológico
O desenvolvimento baseia-se nas seguintes linguagens e bibliotecas:
- **Linguagem:** Python 3.x
- **Visão Computacional:** OpenCV / MediaPipe
- **Machine Learning / Deep Learning:** TensorFlow com Keras
- **Processamento de Dados:** NumPy, Pandas

## 📐 Arquitetura e Metodologia Científica
O fluxo de processamento do modelo segue rigorosos padrões de engenharia de dados e aprendizado de máquina:
1. **Coleta de Dados (Dataset):** Utilização de bases de dados de imagens padronizadas para o treinamento do modelo.
2. **Pré-processamento:** Normalização das imagens, remoção de ruídos e *Data Augmentation*.
3. **Extração de Features:** Identificação das coordenadas espaciais dos movimentos.
4. **Treinamento e Validação:** Ajuste de hiperparâmetros e validação cruzada para evitar *overfitting* e garantir a acurácia do modelo em cenários reais.

## 🚀 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python e o gerenciador de pacotes `pip` instalados. É recomendável o uso de ambientes virtuais (venv ou conda).
