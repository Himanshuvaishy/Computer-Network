# 📘 Explanation of Key IPv4 Concepts

---

## ✅ 1. "Uniquely identifies devices on a network"

Every device (like your laptop, phone, or printer) connected to a network needs a **unique IPv4 address** to communicate properly.

**Think of it like:**
- An IPv4 address is like your **home address**.
- If everyone had the **same address**, mail (data) wouldn’t know where to go.
- So, **each device gets a different IP address**, like:
  - Laptop: `192.168.1.2`
  - Phone: `192.168.1.3`
  - Printer: `192.168.1.4`

🔹 This means no two devices on the same network should have the same IP address.

---

## ✅ 2. "Enables routing of data between devices"

Routers use IP addresses to **send and receive data to the right destination**.

**Imagine:**
- You want to watch a YouTube video.
- Your browser sends a request to YouTube's server IP.
- YouTube replies back, and the **router uses your IP address** to know where to send the video — **to your device, not someone else’s**.

🔹 IPv4 allows routers to **route packets** of data to the correct destination.

---

## ✅ 3. "Can be assigned statically or dynamically"

Devices can receive an IP address in **two ways**:

| Type          | Meaning                                       | Example                     |
|---------------|-----------------------------------------------|-----------------------------|
| **Static IP** | You manually set a fixed IP address.           | `192.168.1.100` (always)    |
| **Dynamic IP**| IP is automatically assigned by DHCP server.   | `192.168.1.10` (may change) |

**Real-life example:**
- When you connect your phone to Wi-Fi, it **automatically gets an IP address** → this is **dynamic**.
- If you set a manual IP in settings → that’s **static**.

---

## 🔁 Summary Table

| Concept                         | What it Means                                  |
|----------------------------------|------------------------------------------------|
| Uniquely identifies devices      | Each device has its own IP                     |
| Enables routing of data          | Routers deliver data to the right device       |
| Assigned statically/dynamically | Fixed manually or given automatically by DHCP  |

---

> Let me know if you’d like diagrams or practice questions!