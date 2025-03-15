# 🍷 Previsão da Cor do Vinho com Métodos Ensemble

## 📌 Descrição do Projeto
Este projeto utiliza algoritmos de **Machine Learning Ensemble** para prever a **cor do vinho** (tinto ou branco) com base em características químicas. Os modelos comparados são:
- **Random Forest** → Modelo baseado em múltiplas árvores de decisão independentes.
- **Gradient Boosting** → Modelo que treina árvores sequencialmente, corrigindo erros anteriores.

---
## 📊 Avaliação dos Modelos
Foram analisadas métricas como **Acurácia, Precisão, Recall e F1-score**, além de **validação cruzada** para evitar overfitting.

📌 **Resultados:**
- **Random Forest** apresentou melhor estabilidade e menor risco de overfitting.
- **Gradient Boosting** teve um desempenho próximo, mas pode ser mais sensível a ruídos.

---
🚀 **Como Executar o Projeto**
# Clone o repositório e acesse a pasta
$ git clone https://github.com/Gabriella-gssp/machine-learning.git
$ cd wine-classification

# Instale as bibliotecas necessárias
pip install -r requirements.txt

# Execute o script principal
python machinelearning.py

Caso utilize Jupyter Notebook, abra:
jupyter notebook

🚀 **Obrigado por conferir este projeto!** 😊