# MSME Transaction-Based Interest Rate Calculator

This repository contains a Python script designed to calculate interest rates for transactions specifically targeting Micro, Small, and Medium Enterprises (MSMEs). Unlike traditional creditworthiness assessments, this approach focuses on transaction-specific metrics, providing a more accurate reflection of an MSME's transactional reliability.

## Overview

Traditional banking systems often pose challenges for MSMEs, such as insufficient credit history, lack of collateral, and burdensome documentation requirements. This script proposes a novel approach by evaluating the financial interactions between businesses through a set of tailored metrics, independent of their traditional credit profile.

## Features

- **Transaction-Specific Assessment**: Calculates interest rates based on transaction-specific data rather than traditional credit scores.
- **7 Key Metrics**: Utilizes a set of seven metrics to assess the transactional reliability of MSMEs.
- **High-Risk Transaction Identification**: Flags high-risk transactions based on the percentage difference between the transaction amount and the average invoice value.

## Metrics Used

1. **Average Invoice Value**
- Indicates scale of transactions
- Large transactions imply more significant business value
- Potential risk / reward scenario

2. **Transaction Frequency**
- Regularity of transactions between the pair of GSTINs
- High frequency → stable business relationship

3. **Average Payment Delay**
- Evaluate promptness of payments
- Faster payments indicate better liquidity
- Low risk of default

4. **Cash Flow Consistency**
- Consistent cash flow indicates a business's ability to manage its finances steadily
- Critical for meeting ongoing operational expenses, debt obligations, and investments.
  
5. **Invoice to Cash Flow Ratio**
- Understanding how much of the business's liquidity is dependent on receivables.
- High ratio can indicate potential cash flow problems if those invoices are delayed or unpaid.

6. **Historical Default Rate**
- A lower historical default rate suggests financial responsibility and reliability
- Leads to potentially lower interest rates.

7. **Tax Compliance Score**
- Measures the MSME’s compliance with tax regulations.
- High compliance score points to responsible financial management
- Reduces perceived risk.

   
