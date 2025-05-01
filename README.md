## 📄 README

### Projeto: Limpeza de Dados de Vinhos Tintos 🍇

**Objetivo:**  
Este projeto tem como propósito praticar técnicas fundamentais de *Data Cleaning* (limpeza de dados) e *Data Preprocessing* (pré-processamento de dados) utilizando um dataset de vinhos tintos.

### 📌 Etapas realizadas:
1. **Verificação de valores nulos:** Nenhum valor nulo encontrado (`df.isnull().sum()`).
2. **Verificação de dados inconsistentes:** Identificação de valores negativos em variáveis onde não deveriam existir (usando `.unique()`).
3. **Remoção de duplicatas:** 240 linhas duplicadas removidas com `.drop_duplicates()`.
4. **Análise de outliers:**  
   - Realizada por meio de boxplots para todas as variáveis.  
   - Alguns valores extremos foram encontrados, mas optou-se por **não removê-los**, pois são possíveis dentro do contexto de vinhos tintos.
5. **Verificação de inconsistências cruzadas:**  
   - Nenhuma ocorrência onde `free sulfur dioxide` fosse maior que `total sulfur dioxide`.

### 📝 Observações:
- O foco do projeto foi exclusivamente a **preparação e limpeza dos dados**, sem aplicação de modelos ou análises estatísticas avançadas.
- As decisões de tratamento foram **documentadas**, priorizando a integridade dos dados reais.

---

## 📄 README

### Project: Red Wine Data Cleaning 🍇

**Purpose:**  
This project aims to practice key techniques in *Data Cleaning* and *Data Preprocessing* using a red wine dataset.

### 📌 Steps completed:
1. **Null value check:** No missing values found (`df.isnull().sum()`).
2. **Inconsistent data check:** Looked for negative values in columns where they shouldn't exist (using `.unique()`).
3. **Duplicate removal:** 240 duplicate rows removed with `.drop_duplicates()`.
4. **Outlier analysis:**  
   - Conducted using boxplots for all numeric variables.  
   - Some extreme values were found, but **not removed**, as they may occur in specific types of red wine.
5. **Cross-variable consistency check:**  
   - No cases where `free sulfur dioxide` was greater than `total sulfur dioxide`.

### 📝 Notes:
- The focus of this project is **data preparation only**, without applying models or advanced statistical analysis.
- All cleaning decisions were **documented**, prioritizing the integrity of real-world data.

