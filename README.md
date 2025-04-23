# 🧠 SMC OPC UA GUI Client

> A secure and real-time OPC UA client built in C# for visualizing and monitoring data from OPC UA System devices.

This application is developed to provide a user-friendly interface for connecting to Systems via OPC UA protocol.  
It allows real-time subscription to multiple nodes, manages certificate-based authentication, and visualizes critical air data such as pressure, flow, and energy usage.

---

## 🚀 Features

- 🔐 **OPC UA secure communication** (with self-signed certificate generation)
- 🔄 **Single-subscription multi-node monitoring**
- 📊 **Real-time data visualization** with customizable polling rate
- 🧩 Modular form structure (Login, UI, Monitor, Polling)
- 💾 Certificate and session management
- 🧠 Built with .NET Framework and Windows Forms

---

## 🧰 Technologies Used

- **C# .NET Framework**
- **Windows Forms (WinForms)**
- **OPC UA .NET Standard SDK**
- **SMC Air Management Devices**

---
## 🔧 How It Works

1. **Launch the GUI** and navigate to the **Server Login** window.
2. **Configure the OPC UA server endpoint** and accept/trust the generated security certificate.
3. Once connected, **node subscriptions are initialized automatically** using a single-subscription strategy.
4. The **MonitorForm** displays real-time data such as pressure, flow, energy usage, and more from the connected to device.
5. You can **adjust polling intervals** dynamically through the **PollingRateForm** for optimized performance and refresh rate.
---
## 📄 License

This project is licensed under the **MIT License**.

You are free to:

- ✅ Use
- ✅ Copy
- ✅ Modify
- ✅ Merge
- ✅ Publish
- ✅ Distribute

**As long as you include proper attribution.**  
There is no warranty — use at your own risk.

For the full license text, see the [`LICENSE`](LICENSE) file in this repository.


