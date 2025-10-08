# Projeto de Visão Computacional – Reconhecimento e Classificação de Formatos de Rosto

## 👩‍💻 Integrantes
- **João Campelo**
- **Laura Garcia**
- **Guilherme Duran**

---

## 📚 Descrição do Projeto
Este projeto faz parte da disciplina de **Visão Computacional** e tem como objetivo na primeira entrega o desenvolvimento de um sistema capaz de:

1. **Reconhecer rostos humanos em imagens**;  
2. **Detectar landmarks faciais (pontos de referência do rosto)**;  
3. **Classificar o formato do rosto** em uma das quatro categorias:  
   - **Quadrado**  
   - **Oval**  
   - **Redondo**  
   - **Triangular**

O trabalho será documentado em formato de **artigo científico**, desenvolvido no [**Overleaf**](https://www.overleaf.com/project/689fdebdee4d86295a58f89e), com base nos resultados e métodos aplicados neste repositório.

---

## 🎯 Objetivos da Primeira Entrega

- [x] Implementar detecção de rosto.  
- [x] Implementar detecção de landmarks faciais.  
- [x] Desenvolver modelo de classificação de formato facial.  

---

## 🧩 Metodologia

O sistema será dividido em três etapas principais:

### 1. **Detecção de Rosto**
Utilizaremos modelos pré-treinados de **OpenCV** ou **dlib** para identificar a região facial em imagens.

### 2. **Detecção de Landmarks Faciais**
Com base no rosto detectado, o modelo de landmarks será aplicado para extrair pontos-chave que vão ser utilizados para a classificação : Testa, Maçãs do rosto, queixo etc

### 3. **Classificação de Formato de Rosto**
Usando as coordenadas dos landmarks, serão extraídas **features geométricas** (como proporções entre distâncias faciais).  
Essas features alimentarão um modelo de **Machine Learning** (como SVM, KNN ou Random Forest) para classificar o rosto em uma das quatro categorias de formato.

---

## ⚙️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.10+**
- **OpenCV** → Detecção de rosto e pré-processamento
- **dlib** → Landmarks faciais
- **NumPy / Pandas** → Manipulação de dados
- **scikit-learn** → Modelos de classificação
- **Matplotlib / Seaborn** → Visualização
- **Jupyter Notebook** → Desenvolvimento e testes

----
