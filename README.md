<h1 align="center"> Projeto de Reconhecimento Facial - Detectando Celebridades</h1>

## Descrição

Esse projeto utiliza o **AWS Rekognition** para detectar celebridades em imagens. A aplicação é construída em Python e utiliza a biblioteca **boto3** para interação com os serviços da AWS. A ideia principal é permitir que, ao enviar uma imagem para o serviço AWS Rekognition, a aplicação retorne os nomes das celebridades presentes na imagem.


## Como Funciona

1. **AWS Rekognition**: O serviço realiza a detecção de celebridades a partir de uma imagem fornecida.
2. **Arquivo `detect_celebs.py`**: Contém o código que interage com o serviço AWS Rekognition, enviando a imagem e recebendo os resultados.
3. **Arquivo `requirements.txt`**: Lista as dependências necessárias para rodar o projeto, incluindo a biblioteca boto3.

## Rodar o Codigo

Antes de rodar o código, você precisa ter os seguintes itens configurados:

- **Conta ativa na AWS**: Certifique-se de ter uma conta na AWS para acessar o serviço Rekognition.
- **AWS CLI configurado**: A AWS CLI deve estar configurada em sua máquina. Execute `aws configure` para configurar suas credenciais da AWS.
- **Python instalado**: O código foi desenvolvido em Python, então é necessário ter o Python instalado no seu sistema.
- **Biblioteca boto3 instalada**: Instale a biblioteca boto3 executando:

Terminal:
- Git bash
  
  "pip install boto3" 

Obs:  **boto3** para interagir com a AWS.

## Tecnologias 

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![boto3](https://img.shields.io/badge/boto3-4B77BE?style=for-the-badge&logo=aws&logoColor=white)
![AWS Rekognition](https://img.shields.io/badge/AWS_Rekognition-FF9900?style=for-the-badge&logo=aws&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)



