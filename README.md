# 🏥 Hospital Length of Stay Analysis & Prediction App

A multi-page Streamlit web application designed to analyze hospital datasets, visualize insights, and predict patient length of stay using Machine Learning techniques.

---

## 🚀 Features

### 📊 1. Summary Dashboard

* Dataset preview
* Statistical summary
* Key Performance Indicators (KPIs):

  * Total Patients
  * Average Length of Stay
  * Maximum Stay
* Missing value analysis

---

### 📈 2. Interactive Visualizations

Built using Plotly for enhanced interactivity:

* Length of Stay Distribution (Histogram)
* Age vs Length of Stay (Scatter Plot)
* Condition vs Length of Stay (Box Plot)
* Year-wise Analysis (Bar Chart)

---

### 🎯 3. Smart Filters (Sidebar)

Apply real-time filters across the entire application:

* Year of Admission
* Gender
* Medical Condition
* Age Range

👉 All dashboards and visualizations update dynamically based on selected filters.

---

### 🤖 4. Machine Learning Prediction

* Model Used: Random Forest Regressor

**Performance Metrics:**

* R² Score
* Mean Absolute Error (MAE)

**Additional Features:**

* Feature Importance Visualization
* Custom user input prediction

---

### 🛠 5. Robust Data Handling

* Handles multiple date formats (DD-MM-YYYY and mixed formats)
* Safe parsing to prevent crashes
* Automatically removes invalid date entries
* Supports custom dataset upload

---

## 📂 Project Structure

```
project-folder/
│
├── app.py                  # Main Streamlit application
├── data/
│   └── hospital_data.csv   # Default dataset (optional)
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/hospital-analysis-app.git
cd hospital-analysis-app
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv myenv

# Activate environment
# Mac/Linux:
source myenv/bin/activate  

# Windows:
myenv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 📦 Requirements

* Python 3.8+
* Streamlit
* Pandas
* Plotly
* Scikit-learn

---

## 📥 Dataset

* Default dataset path:

  ```
  data/hospital_data.csv
  ```

* Users can also upload their own dataset via the sidebar.

---

## ⚠️ Important Notes

* Date formats are automatically handled (DD-MM-YYYY or mixed formats)
* Invalid date rows are safely removed
* Ensure dataset contains required columns:

  * Age
  * Gender
  * Condition
  * Length_of_Stay

---

## 🌟 Future Improvements

* Download filtered reports (CSV / PDF)
* Correlation heatmap
* User authentication system
* Cloud deployment (Streamlit Cloud / AWS)
* UI/UX enhancements

---

## 👨‍💻 Authors

* Kanak Vaishnav


**B.Tech IT | Data Science Enthusiasts**

---

## 📌 License

This project is open-source and available under the MIT License.

---

## ⭐ Support

If you like this project:

* Give it a ⭐ on GitHub
* Share it with others 🚀
