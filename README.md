# SohojTender (সহজটেন্ডার) 🚀
### Intelligent e-GP Tender Automation & Document Management Suite
**Motto:** *LTM — Less Time, More Business* (সহজ টেন্ডার, বেশি ব্যবসা)

[![GitHub Release](https://img.shields.io/badge/Release-v0.0.2-087F5B?style=for-the-badge&logo=github)](https://github.com/rav3n70-1/egp-repo/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-blue?style=for-the-badge&logo=windows)](https://github.com/rav3n70-1/egp-repo/releases/latest)
[![Architecture](https://img.shields.io/badge/Engine-Playwright%20%2B%20PySide6-45475a?style=for-the-badge)](https://github.com/rav3n70-1/egp-repo)

---

## 📌 Overview

**SohojTender** is a high-performance desktop application engineered specifically for Bangladeshi contractors, suppliers, and engineering firms participating in the **National e-GP Portal (`eprocure.gov.bd`)**.

Preparing and submitting tender documents on e-GP often requires hours of tedious manual data entry, repetitive document uploads, and calculations across complex forms. **SohojTender** completely streamlines this process—automating form submissions, mapping compliance documents, and bulk-processing tenders via Excel templates so you spend less time on paperwork and more time winning contracts.

---

## ✨ Key Features

### ⚡ 1. Automated Tender Submission
* Fully automated navigation and interaction with the **e-GP portal (`eprocure.gov.bd`)**.
* Intelligent form-filling for Tender Preparation, Schedules of Requirements, Activity Schedules, and BOQ items.
* Robust error handling and session recovery if portal sessions disconnect.

### 📑 2. Smart Document & ITT Mapping
* **ITT 12.1 Compliance**: Configure documentary evidence for adequacy of liquid assets per tender with exact credit facilities and commitment dates.
* **Per-Tender Document Customization**: Attach specific letters, declarations, and authorization documents tailored to individual tenders.
* **Reusable Document Profiles**: Pre-save corporate certificates, trade licenses, TIN/BIN, and audit reports for instant automated attachment.

### 📊 3. Batch Excel Processing
* **One-Click Template Generation**: Generate pre-formatted `Tender_Template.xlsx` directly to your Desktop or preferred folder.
* **Bulk Import & Execution**: Fill in dozens of Tender IDs, amounts, and dates in Excel, then let SohojTender process them sequentially without supervision.
* **Export & Auditing**: Export processing logs and submission summaries back to Excel for record-keeping.

### 🔒 4. Enterprise-Grade Security
* **Encrypted Credential Storage**: All portal credentials and session tokens are encrypted locally using Windows Data Protection API (DPAPI).
* **Multi-Account Profiles**: Securely manage and switch between multiple e-GP company profiles.
* **Privacy-First Clean Uninstaller**: Completely purges application data, credentials, and cache with zero leftover traces upon uninstallation.

### 🔄 5. In-App Auto-Updater & Cloud Sync
* **Instant Dynamic Plans**: Subscription limits and plan tiers update in real time without needing app restarts.
* **One-Click Updates**: In-app download engine with real-time transfer progress, connecting directly to official releases on this repository.

---

## 🖥️ System Requirements

| Specification | Minimum Requirement | Recommended |
|---|---|---|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 or higher |
| **RAM** | 4 GB | 8 GB or more |
| **Disk Space** | 500 MB free storage | 1 GB SSD storage |
| **Internet** | Stable Broadband / 4G | High-Speed Fiber Internet |

---

## 📥 Download & Installation

1. Navigate to the **[Latest Releases](https://github.com/rav3n70-1/egp-repo/releases/latest)** page.
2. Download the installer: **`SohojTender_Setup_v0.0.2.exe`**.
3. Double-click the downloaded setup file and follow the setup wizard:
   * Select your preferred shortcuts (Desktop & Start Menu).
   * The installer will automatically verify and initialize the required browser components.
4. Launch **SohojTender** from your Desktop shortcut and log in with your registered credentials.

> 💡 **Upgrading from a previous version?**  
> Simply run the latest installer—it will cleanly upgrade your software without affecting your saved tender profiles or local data.

---

## 🚀 Quick Start Guide

### Step 1: Login & Profile Setup
1. Launch **SohojTender**.
2. Enter your account credentials or configure your e-GP profile under **Settings > Profiles**.

### Step 2: Prepare Your Tender Data
1. Navigate to the **Data Manager** tab.
2. Click **Generate Template** and save `Tender_Template.xlsx` to your Desktop.
3. Open the file and enter your tender parameters:
   * `TenderID`
   * `Amount Available`
   * `Dates` (Format: `DD-Mon-YYYY  DD-Mon-YYYY`)
   * `Days` / `Activity Start Days`
4. Click **Import Excel** in the application.

### Step 3: Run Automation
1. Review the imported tenders in the table.
2. Click **Start Workflow** / **Process Tenders**.
3. Sit back while SohojTender automates the document assignment, form submission, and verification.

---

## 🛡️ Uninstallation

To cleanly remove SohojTender:
1. Open Windows **Settings > Apps > Installed apps** (or Control Panel > Programs and Features).
2. Select **SohojTender** and click **Uninstall**.
3. The uninstaller will safely terminate background processes, decrypt and remove all local credential stores (`%LOCALAPPDATA%\SohojTender`), and prompt you to clean temporary browser caches.

---

## 📞 Support & Inquiries

* **Official Website:** [https://sohojtender.com](https://sohojtender.com)
* **Support Email:** [support@sohojtender.com](mailto:support@sohojtender.com)
* **Releases & Updates:** [https://github.com/rav3n70-1/egp-repo/releases](https://github.com/rav3n70-1/egp-repo/releases)

---

<div align="center">
  <sub>Copyright © 2026 SohojTender. All rights reserved.</sub><br>
  <sub><b>LTM — Less Time, More Business</b></sub>
</div>
