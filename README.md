# 🚀 M17 Automation 
**VTU Internship Diary Automation Tool**

M17 Automation is a secure, locally-run desktop application designed to automate the repetitive process of logging daily internship diary entries into the VTU Internyet portal. Built with Python and Selenium, it transforms a week of tedious data entry into a 30-second automated sequence.

### Quick Download
[![Download Latest](https://img.shields.io/badge/Download-M17__Automation__v1.0-10B981?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MadanMS17/M17_Automation/releases/download/v1.0.0/M17_Automation_v1.0.zip)

---

## ✨ Features
* **100% Secure & Local:** Your credentials and data never leave your machine. The app communicates directly with the VTU servers.
* **Bulk Upload:** Write your entire diary in a simple Excel/CSV file and let the bot type it in for you.
* **Dynamic Network Handling:** Choose between Fast, Medium, or Slow network profiles to ensure the bot doesn't crash on slow internet connections.
* **Smart Date Parsing:** Don't worry about formatting; the engine automatically translates your dates into the exact format the portal requires.
* **Live Activity Logs:** Watch the automation happen in real-time through the built-in terminal.

---

## 📥 Installation

1. Download the latest `M17_Automation_v1.0.zip` from the [Releases Page](https://github.com/MadanMS17/M17_Automation/releases/download/v1.0.0/M17_Automation_v1.0.zip
).
2. Right-click the downloaded `.zip` file and select **"Extract All..."**
3. Open the extracted folder and double-click `M17_Automation.exe`.

> **Note on Windows Defender:** Because this is a custom-built indie application, Windows "SmartScreen" or your antivirus might flag it as an "Unrecognized App." This is completely normal for `.exe` files not signed with an expensive corporate certificate. 
> *To bypass:* Click **"More Info"** -> **"Run Anyway"**.

---

## 🛠️ How to Use

### 1. Prepare Your Data
The automation requires a strictly formatted CSV file.
* Click the **"📥 Download CSV Template"** button inside the app to get a blank template.
* Fill in your daily logs. **Do not change the header names** (`date`, `description`, `hours`, `learnings`, `skill`).
* Save the file (ensure it remains in `.csv` format).

### 2. Run the Engine
1. Launch **M17 Automation**.
2. Enter your exact VTU Portal Email and Password.
3. Enter the **exact** Internship Name as it appears in the dropdown menu on the VTU portal (e.g., `	Software Intern`).
4. Click **"📁 Upload CSV"** and select your prepared dataset.
5. Select your Internet Speed (if the VTU portal is loading slowly, choose 'Medium' or 'Slow').
6. Click **"🚀 START AUTOMATION"**.

### ⚠️ Important Warning
If the automation is interrupted (e.g., your internet drops or you close the app mid-run), the bot may have already submitted some entries. **Before running the app again, you MUST open your CSV file and delete the rows for the days that were already successfully submitted.** If you do not delete them, the bot will attempt to log duplicate entries for those days.

