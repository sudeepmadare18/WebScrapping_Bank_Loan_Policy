# Bank Loan Policy

A Streamlit-based web application that displays and compares **Car Loan** and **Personal Loan** policies from different banks.  
The application provides loan details such as loan type, bank, interest rate, loan purpose, tenure, eligibility, processing fee, PolicyBazaar link, and official bank link.

---

# 🌐 Streamlit Application Link

You can access the Bank Loan Policy application using the link below:


> Note: Replace `YOUR_STREAMLIT_APP_LINK` with your actual deployed Streamlit application URL.

Example:

[Click Here to Open the Streamlit App](https://pragyanaipythonprojectloanpolicybazaar-7xizskjfsq3rpe3ypwtden.streamlit.app/)

---

# 📌 Project Overview

Bank Loan Policy is a centralized loan information system built using **Streamlit** and **Pandas**.  
Users can select a loan type such as **Car Loan** or **Personal Loan** and view loan policies offered by different banks.

The system helps users compare loan details such as interest rate, tenure, eligibility, and processing fee in one place.

---

# 🚀 Features

- View Car Loan policies
- View Personal Loan policies
- Display loan details from multiple banks
- Show interest rate, loan purpose, tenure, eligibility, and processing fee
- Provide PolicyBazaar link for each loan
- Provide official bank website link
- Filter loan policies based on loan type
- Simple and interactive Streamlit interface
- Easy loan comparison

---

# 🛠️ Tools and Technologies Used

| Tool / Technology | Purpose |
|---|---|
| **Streamlit** | Used to build the interactive web application |
| **Pandas** | Used for data handling, filtering, and displaying loan policies |
| **Python** | Main programming language |
| **CSV Dataset** | Used to store loan policy details |
| **Streamlit Widgets** | Used for loan type selection, tables, buttons, and links |
| **PolicyBazaar Link** | Provides additional loan information |
| **Official Bank Link** | Directs users to the bank website |

---

# 📂 Loan Policy Dataset

The loan dataset contains the following columns:

| Column Name | Description |
|---|---|
| Loan Type | Car Loan or Personal Loan |
| Bank | Name of the bank or financial institution |
| Interest Rate | Annual interest rate offered by the bank |
| Loan Purpose | Purpose of the loan |
| Tenure | Loan repayment period |
| Eligibility | Basic eligibility conditions |
| Processing Fee | Fee charged by the bank |
| PolicyBazaar Link | Link to PolicyBazaar loan page |
| Official Bank Link | Link to the official bank website |

---

# 🏦 Loan Types

## Car Loan

A Car Loan is a secured loan used to purchase a new or used car.  
The vehicle acts as security until the loan is fully repaid.

## Personal Loan

A Personal Loan is an unsecured loan that can be used for personal expenses such as medical needs, travel, education, or home improvement.  
It does not require collateral.

---

# 🖥️ Application Modules

## 1. Loan Type Selection

Users can select either:

- Car Loan  
- Personal Loan  

## 2. Loan Policy Display

The application displays loan policies from different banks based on the selected loan type.

## 3. Loan Comparison

Users can compare loans based on:

- Interest Rate  
- Tenure  
- Processing Fee  
- Eligibility  

## 4. Bank Links

Users can visit the official bank website or PolicyBazaar page for more details.

---

# 🖥️ Application Workflow

```text
Loan Policy Dataset
        ↓
Pandas Data Processing
        ↓
Streamlit Web Application
        ↓
User Selects Loan Type
        ↓
Loan Policy Filtering
        ↓
Loan Details Display
        ↓
PolicyBazaar / Official Bank Link
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone [https://github.com/your-username/bank-loan-policy.git](https://github.com/your-username/bank-loan-policy.git)
cd bank-loan-policy
```

## 2. Install Required Libraries

```bash
pip install streamlit pandas
```

---

# 📁 Project Structure

```text
bank-loan-policy/
│
├── app.py
├── loan_policy.csv
├── requirements.txt
└── README.md
```

---

# 📄 Sample Dataset

```csv
Loan Type,Bank,Interest Rate,Loan Purpose,Tenure,Eligibility,Processing Fee,PolicyBazaar Link,Official Bank Link
Car Loan,Bank A,8.50%,Car Purchase,3-7 Years,Salaried and Self-Employed,0.50%,[https://www.policybazaar.com,[https://www.banka.com](https://www.banka.com)](https://www.policybazaar.com,[https://www.banka.com](https://www.banka.com))
Personal Loan,Bank B,10.50%,Personal Expenses,1-5 Years,Salaried Individuals,1.00%,[https://www.policybazaar.com,[https://www.bankb.com](https://www.bankb.com)](https://www.policybazaar.com,[https://www.bankb.com](https://www.bankb.com))
```

---

# ▶️ Run the Project

After installing the required libraries, run:

```bash
streamlit run app.py
```

Then open the generated local URL in your browser:

```text
http://localhost:8501
```

---

# 📊 Example Loan Display

| Loan Type | Bank | Interest Rate | Tenure | Processing Fee |
|---|---|---|---|---|
| Car Loan | Bank A | 8.50% | 3–7 Years | 0.50% |
| Personal Loan | Bank B | 10.50% | 1–5 Years | 1.00% |

---

# ✅ Advantages

- Provides loan details from multiple banks in one place
- Helps users compare Car Loans and Personal Loans
- Displays interest rate, tenure, eligibility, and processing fee together
- Saves time compared to visiting individual bank websites
- Provides direct PolicyBazaar and official bank links
- Simple and interactive Streamlit interface
- Easy to extend with more loan types and banks

---

# 🔮 Future Scope

- Add more loan types such as Home Loan, Education Loan, and Business Loan
- Add EMI calculator
- Add loan eligibility checker
- Add filters for interest rate, tenure, and processing fee
- Add bank ratings and customer reviews
- Add loan application tracking
- Use live bank APIs for real-time interest rates
- Add data visualization using Plotly or Matplotlib
- Add user login and saved loan preferences

---

# 🧪 Testing

The application was tested using sample Car Loan and Personal Loan data.

Test cases included:

- Loan type selection
- Loan policy filtering
- Loan details display
- PolicyBazaar link testing
- Official bank link testing
- Streamlit interface testing

---

# 📌 Conclusion

Bank Loan Policy is a simple and useful web application that helps users view and compare Car Loan and Personal Loan policies from different banks.  
It provides important loan details such as interest rate, tenure, eligibility, and processing fee in one place, making loan selection easier and faster.

---

# 👨‍💻 Developed By

**Ajay Saware**  
