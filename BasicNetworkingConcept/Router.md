# 📘 How Routers Assign IP Addresses Using DHCP

---

## ✅ What is DHCP?

> **DHCP** stands for **Dynamic Host Configuration Protocol**.

It’s a protocol that allows a **router** to automatically assign **IP addresses and other network info** to devices (like phones, laptops) when they connect to the network.

---

## 🧠 Why Do We Need DHCP?

Without DHCP, every user would have to **manually configure**:
- IP address
- Subnet mask
- Default gateway
- DNS servers

💡 Imagine having to do that **every time** you joined a new Wi-Fi — no thanks! DHCP makes it automatic and seamless.

---

## 🔁 The 4-Step DHCP Process: DORA

```text
Device ⟷ Router (DHCP Server)
Step	             Name	                                      What Happens
1️⃣	Discover	     Device sends a broadcast:             "Any DHCP here?"
2️⃣	Offer	         Router replies:                    "Here’s an IP I can give you!"
3️⃣	Request	Device:        "Yes,                              please assign me that IP!"
4️⃣	ACK	Router confirms:   "Done!                         You now have that IP."

📦 What Information Does DHCP Assign?
🧾 IP Address: e.g., 192.168.1.12

🌐 Subnet Mask: e.g., 255.255.255.0

🚪 Default Gateway: usually the router’s IP (e.g., 192.168.1.1)

🌎 DNS Servers: e.g., 8.8.8.8 (Google DNS)

🧩 Example of a DHCP Lease
Field	Value
Assigned IP	192.168.1.12
Lease Duration	24 hours
Gateway	192.168.1.1
DNS Server	8.8.8.8

⏳ What Happens When Lease Expires?
After the lease time ends (e.g., 24 hours), the device will request renewal.

If the device stays connected, it usually gets the same IP again.

If it disconnects or shuts down, that IP can be given to someone else.

🛠️ How to See Your DHCP IP (Windows)
bash
Copy
Edit
ipconfig
Look for:

nginx
Copy
Edit

IPv4 Address. . . . . . : 192.168.1.12
Default Gateway. . . . : 192.168.1.1
✅ Can You Use Static IP Instead?
Yes — you can manually assign a static IP on a device. But you must:

Make sure it’s not in the DHCP range

Avoid IP conflicts with others

📋 Summary Table
Feature	                         DHCP	                            Static IP
Assigned by	Router              automatically	                       User manually
Easy to set up	                   ✅ Yes	                            ❌ No, needs manual config
Risk of conflict	        ❌ Low (router manages it)	      ⚠️ High if not done properly
Common use	         Home devices, laptops, phones	                Servers, printers, special devices

✅ DHCP is the brain behind automatically giving IP addresses, keeping your network smart, clean, and conflict-free.


 Summary: Router = Smart Manager
✅ Keeps track of everyone in the network
✅ Manages what goes out and comes in
✅ Protects the internal team from outsiders
✅ Makes sure every reply goes to the right device
✅ Allows all devices to use one shared identity (public IP)