# Microsoft Certified: Dynamics 365 Business Central Functional Consultant (MB-800)

[![Microsoft Certification](https://img.shields.io/badge/Microsoft%20Certified-Business%20Central%20Functional%20Consultant-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Exam Code](https://img.shields.io/badge/Exam%20Code-MB-800-brightgreen?style=for-the-badge&logo=github)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Passing Score](https://img.shields.io/badge/Passing%20Score-700%2F1000-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Practice Materials](https://img.shields.io/badge/Practice%20Materials-MB-800-orange?style=for-the-badge)](https://www.certsclub.com/microsoft/)

---

## 📖 Table of Contents
1. [Exam Overview](#-exam-overview)
2. [How to Prepare](#-how-to-prepare)
3. [Exam Blueprint & Skills Measured](#-exam-blueprint--skills-measured)
4. [Practice & Preparation Materials](#-practice--preparation-materials)
5. [10 Realistic Demo Practice Questions & Answers](#-10-realistic-demo-practice-questions--answers)
6. [Community Discussion & Study Group](#-community-discussion--study-group)
7. [Detailed Topic Documentation Index](#-detailed-topic-documentation-index)
8. [Official Microsoft Learning Resources](#-official-microsoft-learning-resources)

---

## 🎯 Exam Overview

Exam MB-800 validates functional expertise in implementing and configuring Microsoft Dynamics 365 Business Central for small and mid-sized businesses, including financials, sales, purchasing, inventory, and operations.

### Quick Facts
| Attribute | Specification |
| :--- | :--- |
| **Exam Code** | **MB-800** |
| **Certification Name** | **Microsoft Certified: Dynamics 365 Business Central Functional Consultant (MB-800)** |
| **Passing Score** | 700 / 1000 (Scaled Score) |
| **Official Portal** | [Microsoft Learn Credentials](https://learn.microsoft.com/en-us/credentials/certifications/) |

---

## 🚀 How to Prepare

- 🔗 **Review the Exam MB-800 page for exam registration and other details:**  
  Visit the [Official Microsoft Exam Registration Page](https://learn.microsoft.com/en-us/credentials/certifications/) to review scheduling options via Pearson VUE.
  
- 📚 **Explore the Official Study Guide:**  
  Review the official Microsoft study guide for an itemized breakdown of testable objectives.

- 👥 **Connect with Microsoft Training Services Partners:**  
  Find authorized training partners worldwide at the [Microsoft Training Services Partner Directory](https://learn.microsoft.com/en-us/credentials/support/help#training-services-partners).

---

## 📊 Exam Blueprint & Skills Measured

| Domain / Skill Area | Weighting |
| :--- | :---: |
| **Set up Business Central** | **20–25%** |
| **Configure financials** | **25–30%** |
| **Configure sales and purchasing** | **20–25%** |
| **Perform Business Central operations** | **25–30%** |

---

## 💡 Practice & Preparation Materials

For comprehensive practice tests, high-yield scenario questions, and full-length exam simulations, explore the dedicated practice resources for [MB-800](https://www.certsclub.com/microsoft/).

---

## 📝 10 Realistic Demo Practice Questions & Answers

### Question 1 (Domain: Posting Groups)
**Scenario / Question:** In Business Central, which posting matrix combines WHO you sell to/buy from (**Gen. Business Posting Group**) and WHAT you sell/buy (**Gen. Product Posting Group**) to determine the exact General Ledger Sales, COGS, and Purchase accounts?
- A) General Posting Setup
- B) Customer Posting Group
- C) Bank Account Posting Group
- D) Inventory Posting Group
- **Correct Answer:** **A**
- **Detailed Explanation:** The General Posting Setup matrix maps combinations of Gen. Business and Gen. Product posting groups to designated G/L accounts for sales, purchases, discounts, and COGS.

---
### Question 2 (Domain: Data Migration)
**Scenario / Question:** Which built-in tool in Business Central allows functional consultants to export Excel spreadsheet templates, populate legacy master data (Customers, Vendors, Items), and import/validate the data into a new company?
- A) Configuration Packages (RapidStart Services)
- B) Manual SQL Insert
- C) Postman API calls only
- D) Print to PDF
- **Correct Answer:** **A**
- **Detailed Explanation:** Configuration Packages (RapidStart Services) export and import structured Excel sheets to migrate and validate master and setup data into Business Central.

---
### Question 3 (Domain: Dimensions)
**Scenario / Question:** In Business Central, what is the maximum number of **Global Dimensions** that can be defined across the entire application to be available on all ledger entry tables and report filters without recalculation?
- A) 2 Global Dimensions (Global Dimension 1 and 2)
- B) 8 Global Dimensions
- C) 20 Global Dimensions
- D) 100 Global Dimensions
- **Correct Answer:** **A**
- **Detailed Explanation:** Business Central supports exactly 2 Global Dimensions (which are stamped directly on ledger entries) alongside 6 Shortcut Dimensions (for a total of 8 active dimensions).

---
### Question 4 (Domain: Drop Shipments)
**Scenario / Question:** A customer purchases an item that you do not stock in your warehouse. You want your vendor to ship the goods directly to the customer, automatically linking the Sales Order to a Purchase Order. Which feature should you use?
- A) Drop Shipment (using Purchasing Code with Drop Shipment enabled)
- B) Transfer Order
- C) Item Reclassification Journal
- D) Standard Costing
- **Correct Answer:** **A**
- **Detailed Explanation:** Drop Shipments link a sales order line directly to a purchase order, routing goods directly from the vendor to the customer without physical warehouse receipt.

---
### Question 5 (Domain: Year-End Closing)
**Scenario / Question:** Which batch job in Business Central is executed at fiscal year-end to transfer the net balance of all Income Statement accounts into Retained Earnings on the Balance Sheet?
- A) Close Income Statement
- B) Adjust Cost - Item Entries
- C) Post Inventory Cost to G/L
- D) Calculate Depreciation
- **Correct Answer:** **A**
- **Detailed Explanation:** The 'Close Income Statement' batch job calculates net income/loss from income statement accounts and generates balancing closing journal entries into Retained Earnings.

---
### Question 6 (Domain: Item Tracking)
**Scenario / Question:** You sell perishable food items that require tracking by expiration dates and lot numbers. Which Business Central feature must you assign to the Item Card to enforce mandatory lot tracking during receiving and sales picking?
- A) Item Tracking Code
- B) Base Unit of Measure
- C) Tariff No.
- D) Country/Region Code
- **Correct Answer:** **A**
- **Detailed Explanation:** Item Tracking Codes define the tracking parameters (Lot, Serial Number, Expiration date tracking) enforced during inbound and outbound transactions.

---
### Question 7 (Domain: Assembly Management)
**Scenario / Question:** You sell custom computer bundles composed of a CPU, RAM, and Case. You want the system to automatically explode the components and consume raw inventory at the moment the sales order is posted for shipment. What assembly policy should you set on the Item Card?
- A) Assemble-to-Order
- B) Assemble-to-Stock
- C) Purchase-to-Order
- D) Fixed Asset
- **Correct Answer:** **A**
- **Detailed Explanation:** Assemble-to-Order automatically creates a linked Assembly Order when added to a Sales Order, consuming constituent components upon sales shipment.

---
### Question 8 (Domain: Financial Reporting)
**Scenario / Question:** Which feature in Business Central allows accountants to design custom financial statements (such as Balance Sheet, Income Statement, Cash Flow) with custom row formulas and column layouts?
- A) Financial Reports (Account Schedules)
- B) Word Templates
- C) Power Pages
- D) Lifecycle Services
- **Correct Answer:** **A**
- **Detailed Explanation:** Financial Reports (formerly Account Schedules) provide powerful matrix reporting over General Ledger accounts and dimensions.

---
### Question 9 (Domain: Inventory Reclassification)
**Scenario / Question:** You need to change the Bin Code and Department Dimension code on 50 units of inventory in the warehouse without altering quantity or unit cost. Which journal should you post?
- A) Item Reclassification Journal
- B) Item Journal
- C) General Journal
- D) Payment Journal
- **Correct Answer:** **A**
- **Detailed Explanation:** Item Reclassification Journals update metadata attributes (Location, Bin, Dimensions, Serial/Lot numbers) on inventory entries without altering quantities.

---
### Question 10 (Domain: Bank Reconciliation)
**Scenario / Question:** In Business Central, which page allows importing a bank statement file (e.g., CSV/OFX/CAMT) and automatically matching statement lines with bank account ledger entries based on amount and transaction date?
- A) Bank Acc. Reconciliation Page
- B) Payment Journal
- C) General Journal
- D) Chart of Accounts
- **Correct Answer:** **A**
- **Detailed Explanation:** The Bank Account Reconciliation page provides side-by-side automatic and manual matching of external bank statements against recorded ledger entries.

---

## 💬 Community Discussion & Study Group

Have questions regarding MB-800 concepts, study plans, or exam strategies?
- 💬 **Ask a question or start a topic:** [GitHub Discussions](https://github.com/MicrosoftLearnHub/MB-800---Microsoft-Dynamics-365-Business-Central-Functional-Consultant/discussions)
- 🐛 **Report corrections or suggest updates:** [GitHub Issues](https://github.com/MicrosoftLearnHub/MB-800---Microsoft-Dynamics-365-Business-Central-Functional-Consultant/issues)
- 🤝 **Contribute:** Open a Pull Request to share study notes, architecture diagrams, and review materials.

---

## 📂 Detailed Topic Documentation Index

- 📘 [01-setup-business-central.md](./docs/01-setup-business-central.md)
- 📘 [02-configure-financials.md](./docs/02-configure-financials.md)
- 📘 [03-configure-sales-and-purchasing.md](./docs/03-configure-sales-and-purchasing.md)
- 📘 [04-inventory-and-warehousing.md](./docs/04-inventory-and-warehousing.md)
- 📘 [05-assembly-and-production-basics.md](./docs/05-assembly-and-production-basics.md)
- 📘 [06-financial-reporting-and-closing.md](./docs/06-financial-reporting-and-closing.md)
- 📘 [07-official-resources-and-links.md](./docs/07-official-resources-and-links.md)

---

## 🌐 Official Microsoft Learning Resources

- 🌐 [Microsoft Learn Certification Directory](https://learn.microsoft.com/en-us/credentials/certifications/)
- 🌐 [Microsoft Learn Free Interactive Modules](https://learn.microsoft.com/en-us/training/)
- 🌐 [Find a Microsoft Training Services Partner](https://learn.microsoft.com/en-us/credentials/support/help#training-services-partners)

---

### 🛡️ Disclaimer
*This repository contains educational study notes, architecture summaries, and reference documentation compiled from publicly available official Microsoft Learn documentation. Microsoft, Azure, and Microsoft Entra are trademarks of the Microsoft group of companies.*
