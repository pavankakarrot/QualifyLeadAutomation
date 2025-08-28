# Lead Qualification Canvas App + Power Automate Flow

## 📖 Overview
This project is a **Canvas Power App integrated with Power Automate** to demonstrate a lead qualification process in Microsoft Dataverse.  
It is designed as a **portfolio project** to showcase skills in Power Apps, Power Automate, and Dataverse integration.

The app enables sales users to:
- View and search leads
- Apply filters
- Inspect lead details
- Qualify leads into Accounts and Contacts
- Trigger automation using Power Automate for validation and record creation

---

## 🎯 Why This Project
Sales representatives often need a simple and mobile-friendly interface to qualify leads quickly.  
This app replicates a **real-world lead management solution** while highlighting best practices for:
- Canvas App UI/UX
- Dataverse as a backend
- Power Automate for business logic

---

## 🛠️ Architecture
- **Canvas App** → User-facing interface (built in Power Apps)
- **Dataverse** → Stores Leads, Accounts, and Contacts
- **Power Automate Flow** → Handles lead qualification logic:
  - Validates if account/contact already exists
  - Creates new records if needed
  - Associates lead with parent account/contact

---

## 📱 Features
### Canvas App Screens
1. **Lead List Screen** → Search, filter, and select a lead  
2. **Lead Details Screen** → Shows lead info, option to qualify  
3. **Qualify Screen** → Confirms lead to Account/Contact conversion  
4. **Success Screen** → Displays confirmation after qualification  
5. **Error Screen** → Handles failed qualification attempts  
6. **New Lead Screen** → Create a new lead directly  

### Power Automate Flow
- Input from Canvas App
- Initialize variables
- Get lead details
- Check for existing Accounts & Contacts
- Conditional logic
- Create records via Dataverse Web API
- Return response to Canvas App

---

## ⚙️ Setup
1. Import solution into your environment  
2. Configure Dataverse tables:
   - Leads
   - Accounts
   - Contacts  
3. Update Power Automate flow connections  
4. Publish Canvas App  

---

## 🚀 Future Enhancements
- Add error logging to Dataverse custom table  
- Role-based access for Sales vs Managers  
- More detailed dashboards for reporting  

---

## 👨‍💻 Author
Built by *Pavan Kakarrot* as a demonstration of Power Platform expertise.
