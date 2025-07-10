# 📘 Static vs Dynamic IP Address | Public vs Private IP Address

---

## ✅ 1. Static vs Dynamic IP Address

### 🔹 What is a Static IP Address?
A **Static IP address** is manually assigned to a device and **does not change**.

- Set manually by a network admin.
- Remains the same even after reboot.
- Useful for servers, printers, CCTV, etc.

### 🔹 What is a Dynamic IP Address?
A **Dynamic IP address** is **automatically assigned** by a DHCP server and **can change** over time.

- Most common in homes and offices.
- Changes if the device disconnects or restarts.
- Managed by a router or ISP.

---

### 📋 Comparison Table: Static vs Dynamic IP

| Feature           | Static IP                           | Dynamic IP                            |
|------------------|-------------------------------------|----------------------------------------|
| Assignment        | Manual                              | Automatic (via DHCP)                   |
| Changes over time | No                                  | Yes                                    |
| Use Cases         | Servers, printers, CCTV             | Phones, laptops, general home devices  |
| Setup             | Needs manual configuration          | Easy to set up                         |
| Cost (with ISP)   | May require extra cost              | Usually free                           |

---

## ✅ 2. Public vs Private IP Address

### 🔹 What is a Public IP Address?
A **Public IP address** is **globally unique** and assigned by your **ISP**. It allows your device/router to communicate over the **internet**.

- Seen by websites you visit.
- Unique across the entire internet.
- Assigned to your **router**.

### 🔹 What is a Private IP Address?
A **Private IP address** is used **within a local network (LAN)** and is **not routable** on the internet.

- Used for internal communication between devices.
- Assigned by your router using DHCP.
- Not visible to the outside world.

---

### 📋 Reserved Ranges for Private IPs

| Class | Private IP Range               |
|-------|--------------------------------|
| A     | 10.0.0.0 – 10.255.255.255       |
| B     | 172.16.0.0 – 172.31.255.255     |
| C     | 192.168.0.0 – 192.168.255.255   |

---

### 📋 Comparison Table: Public vs Private IP

| Feature           | Public IP                            | Private IP                            |
|------------------|--------------------------------------|----------------------------------------|
| Scope             | Global (Internet)                   | Local (within a network)               |
| Visibility        | Visible to external websites         | Only within internal network           |
| Assigned by       | ISP                                 | Router (via DHCP)                      |
| Uniqueness        | Must be globally unique              | Can be reused in different networks    |
| Example           | `8.8.8.8`, `49.205.120.1`             | `192.168.1.1`, `10.0.0.2`              |

---

## 🧠 Real-World Example:

> 📶 Your **router** gets a **public IP** from the ISP (like `49.205.120.1`).  
> Devices like your phone and laptop get **private IPs** (like `192.168.1.5`) from your router.

---

## 📋 Final Summary Table

| Concept Pair          | Key Difference                                       |
|------------------------|------------------------------------------------------|
| Static vs Dynamic IP   | Manual (permanent) vs Automatic (changes over time)  |
| Public vs Private IP   | Global internet vs Local internal network            |

---


