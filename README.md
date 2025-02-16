# Reconhecimento Facial e Transformação de Imagens em Dados no Azure ML

## 📌 Descrição
Este repositório contém um projeto de **Reconhecimento Facial e OCR (Reconhecimento Óptico de Caracteres)** utilizando o **Azure Machine Learning**. O objetivo é transformar imagens em dados estruturados, demonstrando a capacidade dos serviços cognitivos do Azure.

## 📂 Estrutura do Repositório
```
📁 inputs/   -> Contém as imagens utilizadas para reconhecimento facial e OCR
📁 output/   -> Resultados extraídos das imagens (JSON)
📄 readme.md -> Documentação do processo e insights
```

## 🚀 Passo a Passo do Processo

### 1️⃣ Configuração do Ambiente
1. Criar um recurso **Cognitive Services** no **Azure Portal**.
2. Ativar os serviços de **Face API** e **Computer Vision API**.
3. Obter as **chaves de acesso** e o **endpoint** para uso nas requisições.

### 2️⃣ Reconhecimento Facial
- Utilizamos a **Face API** do Azure para detetar rostos e extrair informações como:
  - Posição e dimensões do rosto
  - Emoções (feliz, triste, neutro, etc.)
  - Idade e gênero estimados

### 3️⃣ OCR - Extração de Texto de Imagens
- Aplicamos a **Computer Vision API** para reconhecimento óptico de caracteres (OCR).
- O modelo extrai textos de imagens e converte para formatos estruturados (JSON, TXT).

### 4️⃣ Salvando os Resultados
- As imagens usadas são armazenadas na pasta `inputs/`.
- Os dados extraídos (detecção facial e OCR) são armazenados em `output/` no formato JSON ou CSV.

## 📊 Insights e Possibilidades
✅ **Automatização de Processos** → Identificação de rostos e extração de informações em larga escala.
✅ **Segurança e Controlo de Acesso** → Uso de reconhecimento facial para autenticação.
✅ **Digitalização de Documentos** → Extração automática de textos para bancos de dados.
✅ **Análise de Sentimentos** → Deteção de emoções em imagens para diversas aplicações.

## 🔗 Links Úteis
- [Lab: Reconhecimento Facial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)
- [Lab: OCR - Extração de Texto](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)
- [Lab: Análise de Imagem](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)
