# Medical-Infusion-Station
 A professional medical infusion monitoring system with multi-language support and pediatric safety protocols.
 #🏥 SmartIV-Pro is a professional-grade medical software designed to monitor and manage IV infusion processes with a focus on pediatric safety and international usability.

🏥Technical Specifications:
SmartIV-Pro1. Localization & Global ComplianceMultilingual User Interface (UI): Full support for English, German, and Turkish, allowing seamless operation for international medical staff [cite: 2025-12-27].Regional Adaptability: Integrated language toggle that updates all system labels, warnings, and prompts in real-time [cite: 2025-12-27].2. Pediatric Safety ProtocolsSmart Dosage Guard: Embedded safety logic that strictly enforces a $2\,\text{ml/kg/hr}$ limit for pediatric patients (under 14 years old) to mitigate medication errors [cite: 2025-12-27].Automated Risk Assessment: Real-time calculation engine that validates infusion parameters against patient-specific physiological data before initiation [cite: 2025-12-27].3. Data Persistence & IntegrityPersistent Configuration: Implementation of a persistent storage system for hospital identification, ensuring the hospital name is retained across system reboots unless manually modified by an administrator [cite: 2025-12-28].Clinical Audit Trail: Automated logging system that records infusion sessions into a hasta_gecmisi.txt file for post-operation review and data integrity [cite: 2025-12-27].4. Software Engineering & DeploymentReal-Time Simulation Engine: High-precision countdown and flow simulation synchronized with system-level time.Professional Deployment: Distributed via a dedicated installer (Inno Setup) featuring desktop shortcuts, registry-safe installation, and uninstallation procedures.Tech Stack: Developed in Python with a Tkinter-based GUI, compiled using PyInstaller for standalone execution.

## 🚀 Key Features

* **Multi-Language Interface:** Fully localized support for **English, German, and Turkish**, making it ready for international medical environments [cite: 2025-12-27].
* **Pediatric Safety Protocol:** Implements a strict $2\,\text{ml/kg/hr}$ safety limit for patients under 14 to prevent dosage errors [cite: 2025-12-27].
* **Data Persistence:** Hospital identity (Hospital Name) and system logs are preserved across sessions to ensure clinical auditability [cite: 2025-12-28, 2025-12-27].
* **Real-Time Simulation:** Advanced countdown and monitoring engine synchronized with universal time.

## 📦 Installation

To use the application:
1.  Download the `SmartIV_Setup.exe` from the repository.
2.  Run the installer (Available in EN, DE, TR).
3.  Launch the application from your desktop shortcut.

## 🛠 Tech Stack
- **Language:** Python
- **GUI:** Tkinter
- **Packaging:** PyInstaller & Inno Setup Compiler

