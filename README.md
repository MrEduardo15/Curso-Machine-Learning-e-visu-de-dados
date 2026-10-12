# 🤖 Curso de Machine Learning, Ciência de Dados e Visualização com Python

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

Este repositório reúne os notebooks, exercícios práticos e conceitos aplicados durante os estudos de **Ciência de Dados, Visualização e Machine Learning** na plataforma **DELL LEAD**. O objetivo é consolidar o domínio prático do ecossistema Python no tratamento, análise exploratória e modelagem preditiva de dados.

---

## 🛠️ Bibliotecas & Ferramentas Utilizadas

| Biblioteca / Ferramenta | Aplicação Prática no Projeto |
| :--- | :--- |
| **Pandas** | Manipulação, filtragem, agrupamento e estruturação de DataFrames. |
| **NumPy** | Operações vetoriais, matrizes numéricas e cálculos estatísticos. |
| **Matplotlib** | Criação e customização de gráficos estatísticos em baixo nível. |
| **Seaborn** | Visualizações estatísticas avançadas e gráficos de alta qualidade visual. |
| **Scikit-Learn (sklearn)** | Pré-processamento, divisão de dados, treinamento e avaliação de modelos. |
| **Jupyter Notebook** | Ambiente iterativo de desenvolvimento e documentação de análises. |

---

## 📚 Conceitos & Funções Aprendidas por Etapa

### 1. 🔍 Análise Exploratória de Dados (EDA) & Tratamento de Dados
* **Inspeção de Dados:** Uso de `.head()`, `.tail()`, `.info()`, `.describe()`, `.shape`, `.dtypes` e `.isnull().sum()` para entender a estrutura e integridade dos dados.
* **Limpeza e Tratamento:** Tratamento de valores ausentes (`.fillna()`, `.dropna()`) e remoção de duplicatas (`.drop_duplicates()`).
* **Manipulação e Agrupamento:** Filtragem condicional, agregação de métricas com `.groupby()`, uso de `.agg()`, ordenação (`.sort_values()`) e criação de colunas derivadas.

### 2. 📊 Visualização de Dados (Data Visualization)
* **Gráficos de Distribuição:** Histogramas (`plt.hist()`, `sns.histplot()`) e KDE plots para verificar a assimetria das variáveis.
* **Detecção de Outliers:** Boxplots (`sns.boxplot()`) para identificar discrepâncias e dispersão interquartil.
* **Relação entre Variáveis:** Gráficos de dispersão (`sns.scatterplot()`, `plt.scatter()`) e gráficos de linha (`sns.lineplot()`).
* **Análise Categórica:** Gráficos de barras (`sns.barplot()`, `sns.countplot()`).
* **Matriz de Correlação:** Heatmaps (`sns.heatmap(df.corr(), annot=True)`) para identificar multicolinearidade e força de associação entre variáveis.

### 3. ⚙️ Pré-Processamento de Dados (Feature Engineering)
* **Codificação de Variáveis Categóricas:** `OneHotEncoder`, `pd.get_dummies()` (para dados nominais) e `LabelEncoder` (para dados ordinais).
* **Escalonamento & Normalização:** `StandardScaler` (z-score) e `MinMaxScaler` (normalização entre 0 e 1) para evitar que variáveis de maior escala viesem o modelo.
* **Divisão dos Dados:** `train_test_split()` garantindo a separação limpa dos dados entre **Treino (Train)** e **Teste (Test)**, evitando *data leakage*.

### 4. 🤖 Machine Learning & Algoritmos
* **Aprendizado Supervisionado - Regressão:**
  * **Conceito:** Predição de valores contínuos.
  * **Modelos:** Regressão Linear (`LinearRegression`).
  * **Métricas:** Erro Médio Absoluto (MAE), Erro Quadrático Médio (MSE), Raiz do Erro Quadrático Médio (RMSE) e Coeficiente de Determinação ($R^2$).
* **Aprendizado Supervisionado - Classificação:**
  * **Conceito:** Predição de categorias/classes discretas.
  * **Modelos:** Regressão Logística (`LogisticRegression`), Árvores de Decisão (`DecisionTreeClassifier`), Random Forest (`RandomForestClassifier`), K-Nearest Neighbors (`KNeighborsClassifier`).
  * **Métricas:** Acurácia (`accuracy_score`), Precisão (`precision_score`), Recall (`recall_score`), F1-Score (`f1_score`) e **Matriz de Confusão** (`confusion_matrix`, `ConfusionMatrixDisplay`).
* **Aprendizado Não Supervisionado - Clustering:**
  * **Conceito:** Agrupamento de dados com base na similaridade, sem rótulos prévios.
  * **Modelos:** K-Means (`KMeans`).
  * **Conceitos:** Método do Cotovelo (Elbow Method / Inertia) para definição do número ideal de clusters ($K$).

### 💡 Conceitos Teóricos Fundamentais
* **Overfitting vs. Underfitting:** Compreensão do equilíbrio entre a capacidade do modelo de generalizar vs. memorizar o conjunto de treino (Bias-Variance Tradeoff).
* **Cross-Validation (Validação Cruzada):** Uso de `cross_val_score` para testar a robustez do modelo em múltiplos folds.
* **Hiperparâmetros:** Ajustes fino de parâmetros (`GridSearchCV` / `RandomizedSearchCV`) para otimização da performance dos algoritmos.

---

## 🚀 Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/MrEduardo15/Curso-Machine-Learning-e-visu-de-dados.git](https://github.com/MrEduardo15/Curso-Machine-Learning-e-visu-de-dados.git)
