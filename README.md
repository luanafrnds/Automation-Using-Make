# Automation Using Make

Streamlining operational workflows through end-to-end automation

This project is a real-world automation built using **Make.com**, designed to eliminate repetitive manual tasks, reduce operational errors, and improve the speed and consistency of communication workflows.

The automation connects **Excel → OneDrive → Outlook**, dynamically retrieves files based on business rules, and generates personalized emails with conditional attachments.  
It replaces a slow, manual billing workflow with a fully automated and scalable solution.

---

## 📌 **Features**

### ✅ 1. Excel Data Extraction  
Reads structured data from a Microsoft 365 Excel spreadsheet, capturing fields such as:

- Insurance Company  
- Product  
- Billing month/year  
- Attachment types  
- Due dates  
- Email  

These values drive the entire automation.

---

### ✅ 2. Dynamic Variable Mapping  
All relevant Excel values are stored using **Set Variables**, ensuring:

- Clean, reusable data  
- No need for iterators  
- No duplicated bundles  
- Predictable logic flow  

---

### ✅ 3. Intelligent File Search (OneDrive)  
The workflow dynamically builds search queries such as:
{company} - {insurer} - {product} - {sequence} - {year}.{month}.pdf

The automation:

- Searches the correct OneDrive folder  
- Finds the exact file that matches the naming pattern  
- Downloads both PDF and XLSX versions (when available)  
- Prevents duplicate searches  

---

### ✅ 4. Automated Email Generation (Outlook):

The automation sends a structured, personalized email with:

- Client's name
- Dynamic message text
- Recesso confirmation request
- Conditional list of attachments
- Fraud prevention instructions
- Embedded e-mail signature hosted on DropBox

---

### 🧩 Technologies Used:
- Make.com: Core workflow automation platform
- Microsoft Excel (365):	Data source
- OneDrive:	File search + retrieval
- Outlook Email API:	Automated email sending
- HTML:	Email formatting
- Conditional Logic:	Dynamic attachment + content generation

---

### 📈 Business Impact:
This automation reduces manual work by:

- 80% decrease in time spent searching for documents

- Zero errors caused by attaching incorrect files

- Consistent communication with clients

- Full traceability of billing messages

- Instant scalability (supports any number of clients/months)

 It transforms a time-consuming, error-prone workflow into a fully automated process.

---

### 🛡️ Data Privacy
All data used in this repository is anonymized.
No real client names, internal IDs, or confidential documents are stored here.

