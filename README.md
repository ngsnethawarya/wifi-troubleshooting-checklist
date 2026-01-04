# Wi-Fi Troubleshooting Checklist (Practical + A+ Friendly)

A clean, step-by-step checklist to troubleshoot Wi-Fi issues fast.
Designed for students, help desk techs, and anyone supporting home/office networks.

## What this repo includes
- Quick fixes (60 seconds)
- Client-side checks (Windows/macOS)
- Router/AP checks
- Common symptoms → likely causes
- When to escalate

---

## 1) 60-Second Quick Fix
- Toggle Wi-Fi OFF/ON
- Turn Airplane Mode ON/OFF
- Forget network → reconnect
- Reboot device
- Reboot router/AP (power off 10 seconds)

---

## 2) Client-Side Checks
### Windows
Open Command Prompt:
```powershell
ipconfig /all
ipconfig /release
ipconfig /renew
ipconfig /flushdns
ping 8.8.8.8
ping google.com

