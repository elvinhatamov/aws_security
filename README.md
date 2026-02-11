# AWS Security Project

This repository contains resources and data files related to AWS security practices and data management for a cloud computing security course (CLCT4011).

## 📋 Overview

This project demonstrates AWS security best practices, data handling, and cloud-based data management principles. The repository includes sample customer and loan data files used for educational purposes in cloud security scenarios.

## 📂 Repository Contents

- **customer-data.csv** - Clean customer information dataset containing:
  - Customer ID
  - Personal information (First Name, Last Name)
  - Contact details (Address, Phone)
  - Join dates

- **customers.csv** - Customer dataset with data quality issues (contains corrupted entry on line 4)

- **loan-data.csv** - Financial loan payment records including:
  - Payment dates
  - Payment amounts
  - Principal and interest breakdown

- **Elvin_Hatamov_CLCT4011-Assignment-v2.pdf** - Course assignment documentation

- **readme.pdf** - Additional project documentation

## 🔒 Security Considerations

This project demonstrates several AWS security concepts:

- **Data Protection**: Handling sensitive customer and financial data
- **Access Control**: Managing data access in cloud environments
- **Data Integrity**: Identifying and handling corrupted data entries
- **Compliance**: Best practices for storing PII (Personally Identifiable Information)

## ⚠️ Data Notice

The data files in this repository contain **sample/educational data only**. Do not use real customer or financial information in this repository.

### Data Quality Issues

Note: `customers.csv` contains a corrupted entry (line 4: "xxxxxxxxxx") demonstrating data validation scenarios.

## 🚀 Usage

These files are intended for:
- AWS security training exercises
- Data handling and validation demonstrations
- Cloud security best practices learning
- Course assignment completion

## 📊 Data Structure

### Customer Data Schema
```csv
CustomerID, First Name, Last Name, Join Date, Street Address, City, State, Phone
```

### Loan Data Schema
```csv
date, description, amount, principal, interest
```

## 🎓 Course Information

- **Course**: CLCT4011 - Cloud Computing Security
- **Student**: Elvin Hatamov
- **Focus**: AWS Security Best Practices

## 📝 License

This project is for educational purposes only.

## 👤 Author

**Elvin Hatamov**
- GitHub: [@elvinhatamov](https://github.com/elvinhatamov)

---

*This repository is part of a cloud computing security course assignment demonstrating AWS security principles and data management practices.*
