# 📊 Exploratory Data Analysis on Job Market Dataset

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on a Job Market dataset to uncover insights about job roles, salaries, required skills, and hiring trends.  
The main goal is to understand patterns in the data and provide useful insights for job seekers and employers.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📂 Dataset
- Source: Kaggle / Job market dataset  
- Contains information about job postings such as:
  - Job Title  
  - Company  
  - Location  
  - Skills Required  
  - Salary Range
 ---

---

## 🔑 Key Steps
1. **Data Cleaning**
   - Handled missing values  
   - Removed duplicates  
   - Standardized column names  

2. **Exploratory Data Analysis**
   - Distribution of job titles and companies  
   - Salary range visualization  
   - Top skills required in the market  
   - Job availability across locations  

3. **Data Visualization**
   - Histograms, bar plots, pie charts, and boxplots  
   - Correlation analysis between job factors  

---

## 📊 Results & Insights
- Identified that **'Data Scientist'** role has moe opportunities among the other roles. 
- Found that **'Amazon.com'** hire the most candidate, follow by **'Ball Aerospace', 'Microsoft'** and **'Google'**.
- The top 5 cities that hire the most data science related job are **'Seattle', 'New York', 'Cambridge', 'Boston',** and **'San Francisco'**.
- **'California'** state has more job opportunities related to Data Science among other states.  

---
---
# 📈 Stock Price Prediction using Linear Regression

## 📌 Overview
This project predicts **future stock prices** based on historical data using **Linear Regression**.  
The goal is to understand market trends and evaluate how well a simple regression model can forecast stock movements.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📂 Dataset
- Source: Stock market dataset (e.g., Yahoo Finance / Kaggle)  
- Features:
  - **Date**: Trading date  
  - **Open, High, Low, Close**: Price points of the stock  
  - **Volume**: Number of shares traded  

---

## 🔑 Key Steps
1. **Data Collection**: Loaded historical stock price dataset  
2. **Data Preprocessing**: Handled missing values and formatted dates  
3. **Exploratory Data Analysis (EDA)**:
   - Trend visualization of stock closing prices  
   - Correlation analysis between features  
4. **Model Building**:
   - Applied **Linear Regression** from Scikit-learn  
   - Trained on historical price data  
5. **Evaluation**:
   - Metrics: R² Score, Mean Squared Error (MSE)  

---

## 📊 Results
- The Linear Regression model captured the trend of stock prices with good accuracy.  
- Achieved an R² Score of **~0.89** (depending on dataset used).  
- Demonstrated the potential of ML for financial forecasting.  

---

## 🚀 How to Run
```bash
git clone <repo-link>
cd Stock-Price-Prediction
pip install -r requirements.txt
jupyter notebook Guru_Stock_Price_Prediction.ipynb




## 🚀 How to Run
```bash
git clone <repo-link>
cd EDA_On_Job_Market

---
---
# 💧 Water Potability Prediction

## 📌 Overview
This project predicts whether water is **safe for drinking (potable)** using **Machine Learning classification models**.  
By analyzing chemical and physical properties of water samples, the model determines if the water meets safety standards.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Logistic Regression, Random Forest, etc.)

---

## 📂 Dataset
- Source: **Kaggle – Water Potability Dataset**  
- Features:
  - pH  
  - Hardness  
  - Solids  
  - Chloramines  
  - Sulfate  
  - Conductivity  
  - Organic Carbon  
  - Trihalomethanes  
  - Turbidity  
  - **Potability (Target: 1 = Safe, 0 = Not Safe)**  

---

## 🔑 Key Steps
1. **Data Preprocessing**
   - Handled missing values (mean/median imputation)  
   - Normalized features for better model performance  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of each chemical feature  
   - Correlation heatmap to check feature importance  

3. **Model Building**
   - Tested classification models (Logistic Regression, Random Forest, Decision Tree)  
   - Evaluated with train-test split  

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score, Confusion Matrix  

---

## 📊 Results
- Best model: **Random Forest Classifier**  
- Achieved accuracy of around **65–70%** (depending on dataset split and tuning)  
- Identified most influential features in predicting water safety (e.g., Sulfate, Chloramines, pH).  

---

## 🚀 How to Run
```bash
git clone <repo-link>
cd Water-Potability-Prediction
pip install -r requirements.txt
jupyter notebook Guru_water_potability_classi.ipynb

---
---
# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Overview
This project uses **K-Means Clustering** to segment mall customers into different groups based on their **Annual Income** and **Spending Score**.  
The goal is to help businesses target the right customer segments for marketing strategies.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (KMeans)

---

## 📂 Dataset
- Source: **Mall Customers Dataset (Kaggle)**  
- Features:
  - CustomerID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  

---

## 🔑 Key Steps
1. **Data Preprocessing**
   - Selected features: Annual Income & Spending Score  
   - Checked for missing values  

2. **Optimal Number of Clusters**
   - Applied **Elbow Method** using WCSS (Within-Cluster Sum of Squares)  

3. **Clustering**
   - Applied KMeans with **k = 5**  
   - Assigned cluster labels to customers  

4. **Visualization**
   - Scatter plot of clusters  
   - Marked centroids for each cluster  

---

## 📊 Results
- Segmented customers into **5 groups**:
  1. Low income – Low spenders  
  2. Low income – High spenders  
  3. High income – Low spenders  
  4. High income – High spenders  
  5. Average income – Average spenders  

- Helps businesses identify **premium customers** and **discount-sensitive groups**.  

---

## 🚀 How to Run
```bash
git clone <repo-link>
cd Customer-Segmentation
pip install -r requirements.txt
jupyter notebook Guru_Customer_Segmentation.ipynb

---
---

---

## 📄 README for **Emotion Detection (CNN)**

```markdown
# 😃 Emotion Detection using CNN

## 📌 Overview
This project uses a **Convolutional Neural Network (CNN)** to classify facial expressions into different **emotions**.  
The dataset consists of grayscale images of faces labeled with emotions such as Happy, Sad, Angry, Fear, Surprise, Neutral, etc.

---

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  

---

## 📂 Dataset
- Source: **FER-2013 Dataset (Kaggle)**  
- Image size: **48x48 pixels**, grayscale  
- Classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral  

---

## 🔑 Key Steps
1. **Data Preprocessing**
   - Rescaled images to [0,1]  
   - Applied **ImageDataGenerator** for augmentation (rotation, zoom, flip)  

2. **Model Architecture**
   - Convolutional Layers (Conv2D)  
   - Pooling Layers (MaxPooling2D)  
   - Dropout for regularization  
   - Dense layers with Softmax for classification  

3. **Training**
   - Optimizer: Adam  
   - Loss: Categorical Crossentropy  
   - Callbacks: ReduceLROnPlateau  

4. **Evaluation**
   - Accuracy and loss curves plotted  
   - Confusion matrix for classification report  

---

## 📊 Results
- Achieved validation accuracy of **~65–70%** (depending on dataset split and tuning).  
- Model successfully distinguishes key emotions like **Happy, Sad, Angry**.  

---

## 🚀 How to Run
```bash
git clone <repo-link>
cd Emotion-Detection-CNN
pip install -r requirements.txt
jupyter notebook Guru_CNN_Project.ipynb

---

---
pip install -r requirements.txt
jupyter notebook EDA_On_Job_Market_Project.ipynb
