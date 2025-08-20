# DNS & IP Address Guide (Mac)

This README provides quick steps to check your *IP Address, **DNS server, view **status codes*, and change DNS servers on macOS.

---

## 1.  IP Address
•⁠  ⁠Type the following in *Terminal*:
  ```bash
  nslookup
Check your DNS IP Address.



---

2.⁠ ⁠ DNS Server

In Terminal, type:

scutil --dns

Check the DNS server IP address.



---

3.⁠ ⁠Checking Status Codes

Open Developer Tools → Ctrl + Shift + I

Go to the Network tab

Click on the request you want to inspect

View status codes (200, 404, 500, etc.)



---
4.  Changing Your DNS Server (macOS)

1. Open System Settings → Network


2. Select your active network (Wi-Fi or Ethernet)


3. Click Details → DNS


4. Remove old entries and add:

Google DNS: 8.8.8.8 and 8.8.4.4

Cloudflare DNS: 1.1.1.1 and 1.0.0.1



5. Click OK → Apply




---

5.  Publicly Available DNS Servers

✅ Google Public DNS

IPv4: 8.8.8.8, 8.8.4.4

IPv6: 2001:4860:4860::8888, 2001:4860:4860::8844


✅ Cloudflare DNS

IPv4: 1.1.1.1

IPv6: 2606:4700:4700::1111




---
