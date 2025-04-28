# PAD Extractor Automation for Supplier X

> **Specialized automated extraction from three different invoice types of Supplier X using Power Automate Desktop.**

---

## 🚀 Project Overview

This project automates the extraction of structured data from batches of **prepayment** and **regular** invoices issued by **Supplier X**.

Two custom-designed **Power Automate Desktop (PAD)** workflows were developed:

- **Prepayment Invoice Flow** – tailored for advance payment invoices
- **Regular Invoice Flow** – tailored for consumption and billing invoices

Both flows extract key fields from PDF invoices and compile them into structured Excel files.

---

## 📂 Project Structure

| Folder | Content |
|--------|---------|
| `/assets/screenshots/prepayment_flow/` | Screenshots & GIF for Prepayment Invoice Automation |
| `/assets/screenshots/regular_flow/` | Screenshots & GIF for Regular Invoice Automation |
| `/assets/outputs/prepayment_output/` | Sample Excel outputs for Prepayment Invoices |
| `/assets/outputs/regular_output/` | Sample Excel outputs for Regular Invoices |

---

## 🛠️ Technologies Used

- **Power Automate Desktop** (Microsoft)
- **Excel** (.xlsx format)
- **PDF Parsing** via PAD native actions
- **ScreenToGif** for recording process demos

---

## 🧩 Key Features

- **Dual automation flows** adapted for invoice type
- **Batch processing** of multiple PDFs
- **Field-level mapping** for supplier-specific invoice formats
- **Error handling** for unexpected file types
- **Structured Excel outputs** ready for analysis

---

## 📽️ Automation Flows in Action

### Prepayment Invoice Flow Demo
![Prepayment Flow Demo](assets/screenshots/prepayment_flow/prepayment_flow_demo.gif)

### Regular Invoice Flow Demo
![Regular Flow Demo](assets/screenshots/regular_flow/regular_flow_demo.gif)

---

## 🖼️ Selected Screenshots

### Prepayment Flow Overview
![Prepayment Overview](assets/screenshots/prepayment_flow/prepayment_flow_overview.png)

### Regular Flow Overview
![Regular Overview](assets/screenshots/regular_flow/regular_flow_overview.png)

---

## 📈 Sample Excel Output

### Prepayment Invoice Output
![Prepayment Excel Output](assets/screenshots/prepayment_flow/prepayment_excel_sample.png)

### Regular Invoice Output
![Regular Excel Output](assets/screenshots/regular_flow/regular_excel_sample.png)

---

## 🎯 Why This Automation Matters

Manually processing invoices is:
- Time-consuming
- Prone to data entry errors
- Inefficient for scaling

By **tailoring the automation** to the supplier's invoice variations, this solution saves:
- Up to **80%** manual processing time
- **Improves data reliability**
- **Simplifies reporting and post-processing**

---

## 📥 How to Use

1. Open **Power Automate Desktop**.
2. Import the **Prepayment Flow** or **Regular Flow** based on the invoice type.
3. Set the input folder containing the PDFs.
4. Run the automation.
5. Collect the generated Excel output for reporting.

---

