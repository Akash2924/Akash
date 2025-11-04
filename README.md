# 📊 PhonePe Data Analytics Dashboard

An interactive **Streamlit-based analytics dashboard** built using data from PhonePe Pulse and PostgreSQL.
This project visualizes **digital payment trends, user growth, and transaction insights** across Indian states, districts, and categories.

---

## 🚀 Features

* **📈 Transaction Analysis:**
  Explore total payments, transaction counts, and amounts by state, district, and year-quarter.

* **🧍‍♂️ User Registration Analysis:**
  Identify top states, districts, and pincodes with the highest number of registered users.

* **🌍 Geo Visualization:**
  Dynamic heatmaps of transactions and users across India.

* **📅 Time-Based Filtering:**
  Filter insights by year and quarter to track digital payment growth over time.

* **📊 Interactive Visuals:**
  Powered by **Plotly**, **Seaborn**, and **Matplotlib** for beautiful data exploration.

---

## 🗂️ Project Structure

```
📦 phonepe-dashboard
│
├── 📄 Phonepe.py                # Main Streamlit app
├── 📄 requirements.txt          # Dependencies list
├── 📄 README.md                 # Documentation
├── 📂 data/                     # CSV or JSON data files (optional)
├── 📂 assets/                   # Logos, images, or icons
└── 📂 database/                 # SQL scripts / PostgreSQL exports
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/phonepe-dashboard.git
cd phonepe-dashboard
```

### 2️⃣ Create a virtual environment (recommended)

```bash
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On macOS/Linux
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🧩 Required Python Libraries

If you don’t have a `requirements.txt`, use this list:

```txt
streamlit
pandas
numpy
plotly
matplotlib
seaborn
psycopg2-binary
```

---

## 🗄️ Database Connection

This project uses **PostgreSQL** to store and fetch PhonePe data.
Make sure to update your database credentials in `Phonepe.py`:

```python
mydp = psycopg2.connect(
    host="localhost",
    user="postgres",
    password="YourPassword",
    port="5432",
    database="phonepe_data"
)
```

---

## ▶️ Running the App

After setup, launch the Streamlit dashboard:

```bash
streamlit run Phonepe.py
```

Then open your browser at:
👉 [http://localhost:8501](http://localhost:8501)

---

## 📷 Sample Screenshots

*Add screenshots here once your dashboard is running.*

```
assets/
 ├── dashboard_home.png
 ├── transaction_heatmap.png
 └── top_states_chart.png
```

---

## 📚 Topics Covered

1. **Transaction Analysis for Market Expansion**
2. **User Registration Analysis**
3. **Insurance & Loan Insights**
4. **App Usage and Engagement Metrics**
5. **Geo Visualization and State Comparison**

---

## 🧠 Future Enhancements

* Integrate live data from PhonePe Pulse API
* Add machine learning forecasting for transaction trends
* Enhance map interactivity with region-level drill-downs
* Deploy the app using Streamlit Cloud or Render

---

## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to modify.

---

## 🧑‍💻 Author

**Akash K**
📧 Email: [akashdurga0924@gmail.com]
🌐 GitHub: [https://github.com/Akash2924/Akash.git]

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
