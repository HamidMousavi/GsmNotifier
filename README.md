# GsmNotifier

A lightweight and modular GSM-based notification system built in Python.  
It allows you to send SMS alerts, monitor SIM card balance, and manage message delivery reports automatically.

## ✨ Features
- **SMS Sending:** Send notifications via GSM modems.
- **Balance Checking:** Automatically check SIM card balance and log results.
- **Notification Queue:** Retry and resend failed messages with smart delay.
- **Logging System:** Detailed logs for sent messages and SIM status.
- **Extensible Design:** Future-ready structure for WebSocket or REST API integration.

## 🧩 Modules
| Module | Description |
|---------|-------------|
| `sms_notifier` | Sends SMS alerts through connected GSM modems |
| `balance_checker` | Retrieves SIM balance and sends low-balance alerts |
| `scheduler` | Manages periodic tasks (SMS retries, balance checks) |
| `logger` | Centralized log handler for all events |

## 🚀 Future Plans
- Add WebSocket & REST API endpoints  
- Real-time dashboard for SMS status and balance monitoring  
- Multi-SIM and distributed notification management  

## ⚙️ Tech Stack
- Python 3.10+
- pySerial
- SQLite (for lightweight local DB)
- Optional: FastAPI (for API support in future)

## 📄 License
MIT License — feel free to use, modify, and contribute.

---

**Author:** Hamid  Mousavi
**Version:** 0.9-beta  
**Status:** Under development 🚧
