# P3CC Disaster Response Portal

Ang **P3CC Disaster Response Portal** ay isang dedicated web-based system na binuo upang mapabilis ang emergency reporting at magbigay ng mabilis na access sa mga emergency hotlines para sa komunidad. Ang system na ito ay naka-integrate sa Google Sheets para sa real-time data logging at email notifications.

## 🛠️ Features
*   **Emergency Reporting System**: Madaling pag-input ng uri ng emergency, lokasyon, at contact details.
*   **Real-time Alerts**: Awtomatikong nagti-trigger ng "RED ALERT" para sa mga kritikal na lugar.
*   **Emergency Hotline Directory**: Mabilis na access sa mga numero ng QCDRRMO at mga kalapit na barangay (Claro, Quirino 3A, Duyan-Duyan).
*   **Google Sheets Backend**: Lahat ng reports ay diretso sa centralized spreadsheet para sa documentation.
*   **Email Notifications**: Awtomatikong pag-send ng email alerts sa mga kinauukulan pagkatapos ng bawat submission.
*   **Interactive Map**: Integration ng Google Maps para sa visual location tracking.
*   **Dark/Light Mode**: User-friendly interface na angkop sa kahit anong kondisyon.

## 💻 Technologies Used
*   **Frontend**: HTML5, CSS3, Vanilla JavaScript
*   **Backend**: Google Apps Script
*   **Database**: Google Sheets
*   **API**: Google Maps JavaScript API
*   **Notifications**: Gmail API (MailApp Service)

## 📋 How to Set Up
1.  **Google Sheets**: Gumawa ng spreadsheet na may tab na pinangalang `EmergencyLogs` at may mga column: `Timestamp`, `Type`, `Location`, `Name`, `Contact`.
2.  **Google Apps Script**:
    *   I-paste ang provided `Code.gs` sa Apps Script editor.
    *   I-deploy bilang **Web App** (Execute as: Me, Who has access: Anyone).
3.  **Frontend**: I-update ang `YOUR_GOOGLE_MAPS_API_KEY` sa `index.html` gamit ang iyong valid API key mula sa Google Cloud Console.

## 👤 Credits
*   **System Developed by**: Tol Ron "INSAN"
*   **Year**: 2026
*   **Organization**: P3CC (Tau Gamma Phi)

> *"A TRISKELION is a brother unto his fellow TRISKELION."*

---
© 2026 P3CC DISASTER PORTAL
