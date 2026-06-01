# 🌐 Network Speed Monitor

A lightweight **C# Windows application** to monitor real-time network bandwidth, download/upload speeds, and IP addresses for all network adapters — with automatic adapter detection and dynamic connection state tracking.

---

## ✨ Features

- **Auto-select active adapter** — detects the currently active network adapter automatically
- **Real-time Download/Upload speed** — live stats updated continuously
- **Peak speed tracking** — records maximum Download/Upload speeds during the session
- **Total data usage** — tracks total Bytes Downloaded and Uploaded
- **IP Address display** — shows both Local and Public IP Address
- **Connection state detection** — dynamically detects if the network is connected or disconnected
- **Works with any adapter type** — Wi-Fi, Ethernet, VPN, etc.
- **Portable** — no installation required, just download and run

---

## 🖥️ Screenshot

![Network Speed Monitor](https://raw.githubusercontent.com/ewwink/NetworkSpeed/master/NetworkSpeed/networkspeed.jpg)

---

## 🚀 Getting Started

### Prerequisites

| OS | Requirement |
|----|-------------|
| Windows 10 and newer | No additional action required |
| Windows 7 and older | Install [.NET Framework 4.6.2](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net462) |

### Download & Run

1. Download the compiled app from the [Releases page](https://github.com/LukeshPawar/NetworkSpeed-/releases)
2. Extract and run the `.exe` — no installation needed

### Build from Source

1. Clone the repository:
   ```bash
   git clone https://github.com/LukeshPawar/NetworkSpeed-.git
   ```
2. Open `NetworkSpeed.sln` in **Visual Studio**
3. Build the solution (`Ctrl + Shift + B`)
4. Run the project (`F5`)

---

## 🛠️ Tech Stack

- **Language:** C# (.NET)
- **Platform:** Windows (WinForms / WPF)
- **Build:** Visual Studio Solution (`.sln`)

---

## 📁 Project Structure

```
NetworkSpeed-/
├── NetworkSpeed/          # Main application source code
├── NetworkSpeed.sln       # Visual Studio solution file
├── main.yml               # CI/CD workflow
└── README.md
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

 

 

 

