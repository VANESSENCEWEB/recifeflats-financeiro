# 📊 Financial Management System - Apartments

📌 This README is also available in other languages:  
- [🇧🇷 Leia em Português](README-pt.md)
  
A web system to manage the financial control of short-term rental apartments for **Recife Flats Temporada Ltda**.

================================================================

## 📋 About the Project

This system allows you to track revenues, expenses, and cash balance for 4 apartments:
- **Apartment 105** – Edifício Ipê (Boa Viagem) – 2 Bedrooms
- **Apartment 203** – Edifício Ipê (Boa Viagem) – 1 Bedroom  
- **Apartment 804** – Edifício Forte São Pedro (Pina) – 2 Bedrooms
- **Apartment 1006** – Edifício Golden View (Boa Viagem) – Flat with Rooftop Pool

---

## 🚀 Features

- ✅ Monthly detailed reports per apartment  
- ✅ Revenue tracking  
- ✅ Management of fixed expenses (condo fee, electricity, internet, property tax)  
- ✅ Tracking of extra expenses  
- ✅ Service provider payments control  
- ✅ Consolidated cash summary  
- ✅ Responsive and modern interface  

---

## 📁 Project Structure

├── index.html              # Main page with list of apartments
├── style.css               # CSS styles for the system
├── template.html           # Base template for any apartment/month
├── 804-resumo.html         # Full summary for Apartment 804
├── agosto-804.html         # Detailed report August 2025 - Apt 804
├── julho-804.html          # Detailed report July 2025 - Apt 804
└── README.md               # This file
└── README-pt.md             # README [🇧🇷 Leia em Português]
...

---

## 📝 About the Template

The **`template.html`** file was created as a **base structure**.  
It contains no data, only the tabs, tables, and cash summary layout.  

### How to use the template:
1. Copy `template.html`.
2. Rename it to match the month and apartment (e.g., `september-105.html`).
3. Edit:
   - Header (`<h1>` and `<h2>`) → update apartment and month.
   - The `dados` array in JavaScript → insert revenues and expenses.

---

## 💻 Example of the `dados` Array

```javascript
const dados = [
  // Revenues
  { data: '05/08/2025', tipo: 'Receita', valor: 1200.00, descricao: 'Airbnb Booking - João Silva' },

  // Fixed Expenses
  { data: '10/08/2025', tipo: 'Despesa', valor: 780.50, descricao: 'Condominium Fee', categoria: 'Fixa' },
  { data: '11/08/2025', tipo: 'Despesa', valor: 300.00, descricao: 'Electricity Bill', categoria: 'Fixa' },

  // Extra Expenses
  { data: '15/08/2025', tipo: 'Despesa', valor: 120.00, descricao: 'Groceries', categoria: 'Extra' },

  // Service Providers
  { data: '20/08/2025', tipo: 'Despesa', valor: 100.00, descricao: 'Admin Gabriela', categoria: 'Prestador' }
];

🌐 How to Use

Option 1: Run Locally
	1.	Download the files
	2.	Open index.html in any browser
	3.	Navigate through apartments and monthly reports

Option 2: GitHub Pages (Recommended)

This system is hosted for free on GitHub Pages:
https://YOURUSERNAME.github.io/REPOSITORYNAME

⸻

🔧 Technologies Used
	•	HTML5 – Page structure
	•	CSS3 – Styling and responsive layout
	•	Vanilla JavaScript – Interactivity and calculations
	•	Responsive Design – Works on desktop and mobile

⸻

📊 Available Reports

By Apartment:
	•	Full cash balance summary
	•	Monthly detailed reports (June to September 2025)

Transaction Categories:
	•	Revenues: Airbnb payments
	•	Fixed Expenses: Condominium fee, electricity, internet, property tax, etc.
	•	Extra Expenses: Groceries, maintenance, Uber, etc.
	•	Service Providers: Administration, accounting, cleaning, etc.

⸻

👥 How to Contribute

=== For Developers: ===

	1.	Fork this repository

	2.	Clone locally:
git clone https://github.com/USERNAME/REPO.git

	3.	Create a branch:
git checkout -b new-feature

	4.	Make your changes

	5.	Commit:
git commit -m "Description of changes"

	6.	Push:
git push origin new-feature

	7.	Open a Pull Request

For Direct Collaborators:
	1.	Clone the repository
	2.	Make the necessary changes
	3.	Commit and push directly to the main branch

⸻

📝 Commit Guidelines

Use descriptive messages:
	•	Add september report for apt 804
	•	Fix fixed expense calculation
	•	Update main page design
	•	Add new apartment 105

⸻

🔄 Regular Updates

The system is updated monthly with:
	•	New financial reports
	•	Airbnb revenues
	•	Current month expenses
	•	Updated cash status

⸻

📞 Support

For questions or issues:
	•	Open an Issue in this repository
	•	Contact management: Recife Flats Temporada Ltda

⸻

📄 License

Internal company use only. Do not distribute without permission.

⸻

Last Update: September 2025
Version: 1.0
Maintainer: Financial Management System

👩‍💻 Author: Vanessa Rafaella

