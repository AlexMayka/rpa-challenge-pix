# 🤖 RPA Challenge Bot (PIX)

This project contains an RPA bot built using the [PIX RPA platform](https://pixrpa.ru/).  
It is designed to complete the [rpachallenge.com](https://www.rpachallenge.com/) task as part of a test assignment.

---

## 🧩 Project Structure
```
pix-project/
├── Main.pixproj                   # Entry point script
├── Framework/
│   ├── ReadConfig.pixproj         # Configuration reader
│   └── WebsiteAutomation.pixproj  # Interaction with the website
├── assets/
│   └── config.xlsx                # Configuration file
```

---

## ⚙️ Functionality

- Loads configuration parameters from external file
- Launches `rpachallenge.com` and fills out web forms
- Follows best practices in modular RPA architecture

---

## 📦 Platform

- **RPA Platform**: PIX
- **Format**: `.pixproj` project files
- **OS**: Windows (tested)

---

## 📝 Notes

This project was developed as part of a test task to demonstrate the ability to automate web-based processes using PIX RPA.
