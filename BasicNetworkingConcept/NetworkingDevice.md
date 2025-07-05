# Networking Devices Explained

## 🔌 1. Host (Computer/Device)
- **What it is**: Any device (like a PC, smartphone, or server) connected to a network.
- **What it does**: Sends and receives data over the network.
- **How it works**: It can request or provide services (like opening a website, sending an email, or storing files).

---

## 🔁 2. Repeater
- **What it is**: A signal booster.
- **What it does**: Amplifies or regenerates weak signals to extend the range of a network.
- **How it works**: Receives a weak signal, strengthens it, and then sends it again to cover longer distances (used in long cable runs or Wi-Fi extenders).

---

## 🔗 3. Hub
- **What it is**: A basic networking device.
- **What it does**: Broadcasts data to all devices connected to it.
- **How it works**: When a host sends data to the hub, the hub sends it to **every device**, regardless of the destination (causing more traffic).

---

## 🔀 4. Switch
- **What it is**: A smarter hub.
- **What it does**: Sends data only to the device it’s intended for.
- **How it works**: Reads the **MAC address** of devices and learns which port is connected to which device — reduces unnecessary traffic and increases performance.

---

## 🌉 5. Bridge
- **What it is**: A device that connects two different LANs.
- **What it does**: Divides a large network into smaller segments or connects two networks.
- **How it works**: Filters traffic and passes data based on MAC addresses.

---

## 🌍 6. Router
- **What it is**: A device that connects **different networks** (e.g., your home to the internet).
- **What it does**: Routes data from your network to other networks (mainly the internet).
- **How it works**: Uses **IP addresses** to determine the best path for forwarding packets to their destination.

---

## 🌐 7. Modem (Modulator-Demodulator)
- **What it is**: A device that connects your network to your **ISP (Internet Service Provider)**.
- **What it does**: Converts **digital data** from your computer to **analog signals** (and vice versa) for transmission over telephone/cable lines.
- **How it works**:  
  - **Modulation**: Converts digital to analog (for sending).  
  - **Demodulation**: Converts analog back to digital (for receiving).

---

## 📍 8. Node
- **What it is**: Any device on the network that can send/receive data (like computers, printers, servers).
- **What it does**: Communicates and participates in network activity.
- **How it works**: Each node has a unique address (like an IP or MAC address) to identify it.

---

## 📡 9. Access Point (AP)
- **What it is**: A device that allows wireless devices to connect to a wired network.
- **What it does**: Acts as a **Wi-Fi transmitter**.
- **How it works**: Connected to a wired network (e.g., router or switch) and broadcasts wireless signals so devices can connect wirelessly.

---

## 📊 Summary Table

| Device         | Function                               | Layer         | Key Role                          |
|----------------|----------------------------------------|---------------|-----------------------------------|
| **Host**       | Sends/receives data                    | Application   | User device                       |
| **Repeater**   | Boosts signals                         | Physical      | Extends network range             |
| **Hub**        | Broadcasts data                        | Physical      | Connects devices (dumb way)       |
| **Switch**     | Sends data intelligently               | Data Link     | Smart device-to-device transfer   |
| **Bridge**     | Connects LAN segments                  | Data Link     | Filters traffic                   |
| **Router**     | Connects different networks            | Network       | Internet access, IP routing       |
| **Modem**      | Connects to ISP                        | Physical/Data | Converts digital ↔ analog         |
| **Node**       | Participates in network                | All layers    | Any addressable network device    |
| **Access Point** | Provides Wi-Fi                       | Data Link     | Wireless access to wired network  |

---
