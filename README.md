# Analisador de Currículos

## Descrição
O **Analisador de Currículos** é um projeto desenvolvido em Python com o objetivo de automatizar a leitura e análise de currículos em formato PDF.  
Utilizando técnicas de Processamento de Linguagem Natural (NLP), o sistema é capaz de extrair informações relevantes como nome, e-mail, telefone, habilidades e experiências profissionais, além de comparar o conteúdo do currículo com a descrição de uma vaga.

Este projeto tem como propósito demonstrar o uso prático de análise textual e aprendizado de máquina em um contexto real de Recursos Humanos.

---

## Objetivos do Projeto
- Facilitar o processo de triagem de currículos.
- Reduzir o tempo de recrutamento inicial.
- Demonstrar conhecimento técnico em Python, NLP e análise de dados.

---

## Tecnologias Utilizadas
- **Python 3.11+**
- **Bibliotecas:**
  - `pdfplumber` — Leitura e extração de texto de arquivos PDF.  
  - `spaCy` ou `NLTK` — Processamento e análise linguística.  
  - `pandas` — Manipulação e estruturação de dados.  
  - `scikit-learn` — (opcional) Modelagem de similaridade entre textos.  

---

## Funcionalidades
- Leitura e extração de texto de currículos em PDF.  
- Identificação automática de nome, e-mail e telefone.  
- Detecção de palavras-chave e principais habilidades.  
- Comparação entre currículo e vaga, gerando uma pontuação de compatibilidade.  
- Exportação dos resultados para formatos `.csv` ou `.json`.

---

## Estrutura do Projeto
