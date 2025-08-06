# E-Commerce-Website-Development-using-React-
A full-featured E-Commerce website built using React.js with product listing, cart management, search functionality, and responsive design.
# 🛒 E-commerce Web App Automated Testing Suite

An automated test framework for testing critical workflows (login, search, add to cart, checkout) in an e-commerce website using Selenium and Python.

## ⚙️ Tech Stack
- Selenium WebDriver
- Python + PyTest
- ChromeDriver
- GitHub Actions (CI/CD)
- HTML Reports

## 🧪 Test Scenarios
- ✅ User login/logout
- ✅ Product search and filtering
- ✅ Add/remove items in cart
- ✅ Checkout process validation

## 🔍 Folder Structure
ecommerce-tests/
├── tests/
│ ├── test_login.py
│ ├── test_search.py
│ └── test_checkout.py
├── reports/
├── conftest.py
├── requirements.txt
└── README.md

## 🚀 How to Run Tests
```bash
pip install -r requirements.txt
pytest --html=reports/report.html

