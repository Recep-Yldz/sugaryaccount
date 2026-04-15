# 🍬 Sugar Finance (Şekerli Hesap): AI-Powered Financial Navigation System

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)](https://flutter.dev)
[![Gemini AI](https://img.shields.io/badge/Gemini%20AI-8E75B2.svg?style=for-the-badge&logo=google-gemini&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![Security](https://img.shields.io/badge/Security-Audit--Passed-success.svg?style=for-the-badge&logo=cloudera&logoColor=white)](#-cybersecurity-analysis)

**Sugar Finance** is an "Algorithmic Accounting" and profit analysis engine designed to solve financial complexity for sole proprietorships and small businesses. Powered by **Google Gemini AI**.

---

## 📱 App Preview

<div align="center">
  <table border="0">
    <tr>
      <td width="50%" align="center">
        <img src="main_screen.jpg" alt="Dashboard" width="250px"/><br>
        <b>Financial Overview & Tracking</b>
      </td>
      <td width="50%" align="center">
        <img src="analysis.jpg" alt="AI Analysis" width="250px"/><br>
        <b>Gemini AI Strategic Insights</b>
      </td>
    </tr>
  </table>
</div>

---

## 🎯 Problem Statement
Most small business owners confuse revenue (total cash flow) with net profit. Calculating the "Real Net Profit" is challenging due to VAT (KDV), withholding taxes (stopaj), income tax reserves, and operational overhead. 

**The Solution:** Sugar Finance automatically deducts all legal and operational shares from every sale. It provides professional **KPIs** such as **ROI (Return on Investment)**, **Gross Margin**, and **Net Unit Profit** as if you had a dedicated CFO.

## 🛠️ Technical Architecture
* **Framework:** Flutter & Dart for high-performance cross-platform experience.
* **State Management:** `ChangeNotifier` & `ListenableBuilder` for reactive UI updates.
* **Intelligence Layer:** Integrated with `Gemini Flash-Latest` via `google_generative_ai` for executive summaries and strategic advice.
* **Data Visualization:** `fl_chart` for rendering complex weekly profit flows and financial distributions.
* **Hybrid Storage:** * `shared_preferences` for general settings.
    * `flutter_secure_storage` (Keystore/Keychain) for sensitive API credentials.

## 🔒 Cybersecurity Analysis (Aspirant Perspective)
The system is built with a "Security-by-Design" approach, focusing on the following vulnerability assessments:

* **Data-at-Rest Protection:** Identified risks regarding plain-text storage in `shared_preferences`. Future roadmap includes **AES-256 encryption** for sensitive financial records.
* **Physical Access Security:** Proposed integration of `local_auth` (Biometric FaceID/Fingerprint) to protect commercial secrets from unauthorized physical access.
* **Reverse Engineering Defense:** Deployment of **Code Obfuscation** techniques during the build process to protect the proprietary logic in `gemini_service.dart`.
* **Input Sanitization:** Implementation of strict **Schema Validation** for JSON data imports to prevent logic-based attacks or crashes.

## 📊 Key Features
- **Dynamic Tax Engine:** Instant calculation of VAT, withholding tax, and social security (Bağkur) fees.
- **AI Financial Consultant:** An integrated AI that analyzes your data to suggest efficiency improvements.
- **Detailed Analytics:** Professional financial metrics displayed through intuitive charts.

---

### 👨‍💻 Developer
**Kemal** *Software Development Student & Cybersecurity Aspirant*

---
*Developed to empower the digital financial transformation of small enterprises.*
