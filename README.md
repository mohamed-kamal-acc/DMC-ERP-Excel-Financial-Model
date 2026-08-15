# 📊 DMC ERP Architecture on Excel — Integrated Operational & Financial Framework

> **Project Status:** 🟡 *Under Active Development (Release Expected Soon)*  
> **Author & Designer:** Mohamed Kamal — *Senior Income & Financial Accountant*

An experimental framework and 25-sheet Excel-based ERP architecture designed to solve the structural gap between **Frontline Operations** and **Financial Accounting/IFRS/EAS** in Destination Management Companies (DMCs).

---

## 🛑 Problem Definition: The DMC Accounting Challenge
In tourism DMCs, a major gap exists between two distinct perspectives:
* **Operational View:** Deals in multi-currency (€ / $), estimates supplier costs (Hotels, Flight, Nile Cruises, Excursions), focuses on *Gross Margin per Group*, and handles constant itinerary modifications[cite: 1].
* **Financial View:** Complies with IFRS/EAS revenue recognition, processes 14% Input VAT, handles WHT tax deductions, calculates Foreign Exchange (FX) Gains/Losses, and issues official tax invoices[cite: 1].

---

## 🔄 Operational Workflow (4 Key Stages)
1. **Booking Confirmation:** Recording advance payments received from foreign tour operators[cite: 1].
2. **Operational Vouchers:** Issuing service vouchers for hotels, transport, and guides[cite: 1].
3. **Tour Operations:** Executing the program and logging real-time field costs[cite: 1].
4. **Audit & Closing:** Reconciling supplier bills, separating 14% VAT input, and generating final tax invoices[cite: 1].

---

## ⚡ Automated Accounting Engine
The core engine routes operational actions into automated general ledger entries without manual re-entry[cite: 1]:

| Operational Event | Debit (مدين) | Credit (دائن) | Financial Impact |
| :--- | :--- | :--- | :--- |
| **Advance Receipt** | Bank Account (FX) | Customers - Advance Payments | Cash inflow & FX rate locking[cite: 1] |
| **Supplier Advance** | Suppliers - Advance Payments | Bank Account | Pre-invoice supplier payment[cite: 1] |
| **Final Billing** | Customers - Tour Booking | DMC Service Revenue + VAT | Revenue recognition & tax liability[cite: 1] |
| **Supplier Invoicing** | Net Cost + 14% Input VAT | Supplier Accounts | Net cost recording & Input VAT separation[cite: 1] |
| **Supplier Settlement**| Supplier Accounts | WHT Payable + Bank (Net) | WHT tax deduction & final payment[cite: 1] |

---

## 🛡️ Governance & Controls
* **Automated Ledger Entries:** Prevents manual overrides from operational screens[cite: 1].
* **Audit Trail:** One-click drill-down to original transactions and vouchers[cite: 1].
* **Balanced Trial Balance:** Built-in dynamic Chart of Accounts integration[cite: 1].

---

## 📁 Project Attachments & Documents
This repository hosts the full technical ecosystem:
* 🟢 **`DMC_ERP_Financial_Model.xlsx`** *(25-Sheet Excel System)*
* 📄 **`DMC_ERP_Presentation.pdf`** *(Case Study & Technical Integration Deck)*
* 📑 **`Practical_Case_Study.pdf`** *(Step-by-Step Transaction Walkthrough)*
* 📘 **`ERP_SaaS_Specifications.pdf`** *(Functional Requirements Guide for Odoo/SAP Implementations)*

---

### 📬 Discussion & Knowledge Sharing
Open to discussions on DMC financial modeling and ERP implementation strategies!
* **LinkedIn:** [Mohamed Kamal Profile](https://www.linkedin.com/in/mohamed-kamal-368b39b2/)[cite: 1]
* **Email:** [mohamedk5051@gmail.com](mailto:mohamedk5051@gmail.com)
