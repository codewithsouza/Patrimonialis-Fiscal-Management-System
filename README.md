# 📊 Fiscal Management System – Patrimonialis
> ⚠️ This project is currently under development.


A complete platform for managing corporate tax debts, legal processes, and customer portfolios. Designed to help fiscal/legal consultancies monitor debts at federal, state, and municipal levels, simulate payments, and track negotiations and legal actions.

---

## 🚀 Stack Used

`Flask` · `Python` · `PostgreSQL` · `JavaScript` · `Bootstrap` · `TailwindCSS`

---

## 🔐 User Roles

- **Administrator**: Full system access, including client and debt management
- **Client**: Limited access to their own dashboard, debts, and notifications

---

## ⚙️ Key Features

### ✅ Admin Dashboard
- Overview of total clients, debt value, active legal processes, and weekly events
- Quick access to system-wide statistics and notifications

### 👥 Client Management
- Register, edit, delete clients with full details (name, CNPJ, tax regime, segment, etc.)
- Export client data to Excel/CSV
- (Import via file – in development)

### 💸 Debt Management
- Track federal, state, and municipal debts by client
- Filter by type (IPTU, ISS, fees, fines), date range, city, and status
- Simulate payments and monitor outstanding balances
- Add new debts through the interface

### ⚖️ Legal Process Management
- Follow legal/judicial processes per client
- See statuses, updates, and movement history

### 📬 Notifications & Events
- Send system notifications to clients
- Manage and view event reminders

### 🤝 Negotiations
- Track ongoing negotiations with clients
- Record proposals, agreements, and negotiation history

### 🔐 Authentication & Access Control
- Secure login/logout for admins and clients
- New admin registration with authorization code
- Flask-Login based session management

---

## 👤 Client Portal

### 🏠 Dashboard
- View personal info and a summary of debts, negotiations, and legal processes

### 💰 Debt Overview
- Filterable list of active debts with simulation tools

### 📑 Negotiations
- View active proposals, accept deals, and access history

### ⚖️ Processes
- Follow all ongoing legal processes linked to the account

### 📢 Notifications
- Receive important updates and messages from admins

---

## 📱 UI & Security

- **Responsive Interface** using Bootstrap and TailwindCSS
- **Secure Session Handling** with Flask-Login
- **Clear role separation** between admin and client

---

## 📤 Export / Import

- Export data (e.g., clients) to spreadsheet formats
- Client import via file (feature under development)

---

📌 *This project is structured with scalability, security, and usability in mind — ideal for consultancies or legal teams managing high client volume and sensitive fiscal data.*
