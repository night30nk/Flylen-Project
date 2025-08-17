# Flylen Pulse - Analytics Dashboard  

**Flylen Pulse** is an internal **Analytics Dashboard** built by Flylen, designed to track everything that matters for the company.  
From **employee performance** to **project progress** and **team productivity**, Pulse gives managers and teams a clear picture of what’s happening in real time.  

---

## 🚀 Purpose  

- Track **KPIs** (Key Performance Indicators) across teams  
- Monitor **employee performance** and engagement  
- Follow up on **projects** with deadlines, budgets, and progress  
- Visualize data with **interactive charts & reports**  
- Centralize company insights in one clean dashboard  

---

## 🎯 Features  

- 📊 **Top KPIs at a glance** – Active Projects, Employee KPIs, Completed Tasks, Revenue vs Budget  
- 🗂 **Project Tracker** – Manage project names, members, deadlines, and completion %  
- 👥 **Employee Analytics** – Track performance scores and activity logs  
- 📈 **Charts & Reports** – Productivity graphs, progress timelines, KPI tracking  
- 🔔 **Recent Activity Feed** – View latest team updates, submissions, or milestones  
- 🎨 **Modern UI** – Clean Material Dashboard design customized for Flylen  
- 🔒 **Authentication Ready** – Secure access with login system  
- ⚡ **Scalable** – Works with SQLite by default, can switch to PostgreSQL/MySQL  

---

## 📂 Layout  

- **Sidebar Navigation**  
  - Dashboard  
  - Usage Tracker  
  - Energy & Network Charts
  - Project Tracker
  - Analytics
  - Notifications
  - Map  
  - Settings  

- **Top Stats Cards**  
  - Active Projects  
  - Employee KPI %  
  - Tasks Completed Today  
  - Revenue / Budget  

- **Charts Section**  
  - Employee Productivity (per team/department)  
  - Project Progress (line chart over time)  
  - KPI Tracking (goals vs. achieved)  

- **Tables & Feeds**  
  - Projects Table → Track projects with members, deadlines, progress %  
  - Recent History → Latest company/team updates  

---

## 🛠 Tech Stack  

Flylen Pulse uses both **Frontend** and **Backend** technologies.  
Right now, the **Frontend is the main focus**, while the Backend is still under development.  

- 🎨 **Frontend**  
  - **Bootstrap 5 + Material Dashboard** – Modern UI & responsive design  
  - **HTML5, CSS3, JavaScript** – Core structure & styling  
  - **Jinja2 Templates** – Dynamic rendering for Flask integration  

- ⚙️ **Backend** (Work in Progress 🚧)  
  - **Flask (Python)** – Planned backend framework  
  - **SQLite (default), PostgreSQL/MySQL (planned)** – Database support  
  - **REST APIs** – To connect projects, employee data, and reports (coming soon)  

- 📊 **Other Tools**  
  - **Dynamic DataTables** – Manage and visualize data easily  
  - **Charts & Graphs** – For KPIs, productivity, and progress tracking  


---

## 🔧 How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/night30nk/Flylen-Project.git
   cd Flylen-Project

2. Create a virtual environment
   ``` bash
   pip install -r requirements.txt

3. Run the app
   ``` bash
   python run.py