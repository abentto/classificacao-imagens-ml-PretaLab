# 🧠 Classificação de Imagens com Machine Learning – PretaLab

Este projeto foi desenvolvido como parte das atividades do curso de Introdução à Inteligência Artificial da PretaLab. O objetivo foi utilizar um modelo de **Machine Learning para classificação de imagens humanas por características raciais**.

O modelo pré-treinado faz a inferência (classificação) a partir de uma imagem fornecida, retornando a probabilidade de pertencer a uma das classes possíveis.

---

## 📌 Tecnologias Utilizadas

- [Google Colab](https://colab.research.google.com/)
- Python
- Biblioteca `transformers` da Hugging Face
- Biblioteca `PIL` (Python Imaging Library)
- Modelo `google/vit-base-patch32-384`

---

## ⚙️ Como Executar

1. Acesse o notebook diretamente pelo Google Colab.
2. Execute as células na ordem.
3. Uma imagem é baixada da internet usando o comando `!wget`.
4. A imagem é carregada com a biblioteca `PIL`.
5. O modelo `pipeline` da Hugging Face realiza a classificação da imagem.

---

## 🗂 Estrutura do Projeto

📦 classificacao-imagens-ml-PretaLab
┣ 📄 classificacao_por_raca.ipynb
┗ 📄 README.md


---

## 💡 Observações

- Este projeto é educacional e utiliza um modelo pré-treinado para fins de demonstração.
- As classes de saída são baseadas no modelo da Hugging Face e não foram treinadas especificamente por esta equipe.

---

## 👩🏾‍💻 Desenvolvido por

Projeto desenvolvido por Aghata Bentto(https://github.com/abentto), participante da Ciclo Formativo em IA  do PretaLab, 2025.


