# PAD Extractor Automation for Supplier Elindus

> **Specialized automated extraction from three different invoice types of Elindus (elindus.be), a Belgian energy supplier, using Power Automate Desktop.**

---

## 🚀 Project Overview

This project automates the extraction of structured data from two invoice types issued by **Elindus**:

- **Prepayment Invoices** (advance billing)
- **Regular Invoices** (consumption-based billing)

Two customized **Power Automate Desktop (PAD)** workflows were developed to process each invoice type independently.  
The automations generate structured Excel outputs for further analysis.

---

## 📂 Project Structure

| Folder | Content |
|--------|---------|
| `/assets/screenshots/prepayment_flow/` | Screenshots & GIFs related to prepayment invoice automation |
| `/assets/screenshots/regular_flow/` | Screenshots & GIFs related to regular invoice automation |
| `/assets/outputs/prepayment_output/` | Sample Excel outputs for prepayment invoices |
| `/assets/outputs/regular_output/` | Sample Excel outputs for regular invoices |

---

## 🛠️ Technologies Used

- **Power Automate Desktop** (Microsoft)
- **Excel** (.xlsx format)
- **PDF Parsing** via PAD native actions
- **ScreenToGif** for animated process demos

---

## 🧩 Key Features

- **Separate automation flows** per invoice type
- **Excel mapping preparation** prior to extraction
- **Error handling and batch processing**
- **Adaptation to Elindus-specific invoice formats**
- **Structured Excel outputs optimized for reporting**

---

## 📽️ End-to-End Process Demonstrations

### 1. Regular Invoice Processing

#### 📝 Excel Input Preparation (Regular Invoice)
![Regular Excel Input GIF](assets/outputs/regular_output/PDF_extractor_regular_invoices_excel_input.gif)

#### ⚙️ PAD Automation Flow (Regular Invoice)
![Regular PAD Flow GIF](assets/outputs/regular_output/PDF_extractor_regular_invoices_pad_flow.gif)

---

### 2. Prepayment Invoice Processing

#### 📝 Excel Input Preparation (Prepayment Invoice)
![Prepayment Excel Input GIF](assets/outputs/prepayment_output/PDF_extractor_prepayment_invoices_excel_input.gif)

#### ⚙️ PAD Automation Flow (Prepayment Invoice)
![Prepayment PAD Flow GIF](assets/outputs/prepayment_output/PDF_extractor_prepayment_invoices_pad_flow.gif)

---

## 🖼️ Example Invoices and Outputs

### 📄 Sample Invoices (PDF screenshots)

#### Prepayment Invoice Example (Elindus)
![Prepayment Invoice Screenshot](assets/screenshots/prepayment_flow/Elindus_prepayment_bill_sample.png)

#### Regular Invoice Example (Elindus)
![Regular Invoice Screenshot](assets/screenshots/regular_flow/Elindus_regular_bill_sample_1.png)

---

### 📈 Sample Excel Outputs

#### Prepayment Invoice Output (Excel)
![Prepayment Excel Output](assets/screenshots/prepayment_flow/prepayment_invoices_extracted_excel.png)

#### Regular Invoice Output (Excel)
![Regular Excel Output](assets/screenshots/regular_flow/Regular_invoices_extracted_excel.png)

---

## 🎯 Why This Automation Matters

Manual invoice processing:
- Is **time-consuming**  
- Leads to **data entry errors**  
- Delays **financial reporting**

By tailoring the automation to **Elindus' invoice templates**, this solution:
- Reduces manual input time by up to **80%**
- Improves **data accuracy**
- Provides **ready-to-analyze Excel outputs**

---

## 📥 How it Works

1. Opens **Power Automate Desktop**.
2. Imports the **Prepayment Flow** or **Regular Flow** based on the invoice type.
3. Checks the input folder containing the PDFs.
4. Runs the automation.
5. Extracts the data
6. Enters the extracted output into Excel automatically.

---




