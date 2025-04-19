# PowerShell Active Directory Onboarding Lab 🖥️

## 🔍 Overview
This lab simulates a real-world IT Help Desk task — onboarding a new user into Active Directory using PowerShell. I built the environment in **Azure**, created a Windows Server VM, promoted it to a domain controller, and fully automated the user creation process with logging.

---

## 🛠️ Tools Used
- 💻 Azure Virtual Machine (Windows Server 2022)
- 🧩 Active Directory Domain Services (AD DS)
- ⚡ PowerShell + PowerShell ISE
- 🖧 Microsoft Remote Desktop (RDP from macOS)

---

## 📜 Script Features
- Prompts for user info (first name, last name, department)
- Automatically generates username
- Creates AD user in correct Organizational Unit (OU)
- Adds user to department group (e.g., IT Users)
- Saves a log entry to a `.csv` file for auditing

---

## 🧪 Screenshots (Full Workflow)

powershell-ad-onboarding-lab/
├── onboarding-script.ps1
├── README.md
├── screenshots/
│   ├── 01-promote-to-dc.png
│   ├── 02-login-domain.png
│   ├── 03-create-logs-folder.png
│   ├── 04-run-onboarding-script.png
│   ├── 05-user-created-in-ou.png
│   └── ad_lab_showcase_combined.png


---

## 💾 Project Structure

