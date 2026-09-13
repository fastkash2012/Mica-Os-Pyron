# Mica OS Pyron

> A modern, experimental web-powered operating system experience built with Python, FastAPI, PyQt6, and a custom liquid-glass desktop interface.

**Mica OS Pyron** is a feature-rich desktop environment and operating system simulation that combines a modern web interface with a Python-powered backend. It features a complete desktop experience, application system, file management, authentication, themes, plugins, system tools, and native desktop support.

🌐 **Live Demo:** [Mica OS Pyron](https://micaos-pyron.netlify.app/?utm_source=chatgpt.com)

---

## ✨ Features

### 🖥️ Modern Desktop Experience

* Modern desktop environment
* Liquid glass / glassmorphism inspired interface
* Interactive app dock and taskbar
* Window management system
* Lock screen and onboarding experience
* User accounts and Guest Mode
* Handwritten welcome splash screen
* Wallpapers and themes
* Responsive interface

### 📦 Built-in Applications

Mica OS Pyron includes a collection of built-in system and creative applications:

* ⚙️ **Amber Settings** — System settings and customization
* 🎨 **Beryl Studio** — Creative workspace
* 📷 **Camera** — Camera application
* 🖌️ **Creative Centre** — Creative tools and workspace
* 📁 **Jade Explorer** — File explorer
* 💻 **Onyx Terminal** — Terminal environment
* 📦 **Package Manager** — Application and package management
* 🧊 **Prism3D** — 3D creative environment
* 🌐 **Pyro Browser** — Built-in web browser
* 🐍 **Python Lab** — Python development environment
* ✏️ **Ruby Editor** — Text and code editor
* 🎵 **Vynl** — Media experience

---

## 🔐 User System

Mica OS Pyron includes a complete account and onboarding experience.

Features include:

* User authentication
* Account creation
* First-run onboarding
* Lock screen
* Guest Mode
* Secure backend authentication
* Security and encryption utilities

---

## 🎨 Themes & Customization

Personalize your Mica OS environment with:

* Custom wallpapers
* Theme management
* User themes
* Desktop customization
* Modern liquid-glass UI
* Personalized application environment

Included wallpapers include:

* Aurora Monterey
* Bloom Ventura

---

## 🔌 Extensible Architecture

Mica OS Pyron is designed with modularity in mind.

### Application System

Applications are organized into separate directories and use application configuration files.

```text
apps/
├── system/
│   ├── amber_settings/
│   ├── beryl_studio/
│   ├── camera/
│   ├── creative_centre/
│   ├── jade_explorer/
│   ├── onyx_terminal/
│   ├── package_manager/
│   ├── prism3d/
│   ├── pyro_browser/
│   ├── python_lab/
│   ├── ruby_editor/
│   └── vynl/
│
└── user/
```

### Plugin Support

Mica OS Pyron also includes a plugin architecture:

```text
plugins/
└── user/
```

This allows the operating system to be expanded with additional functionality.

---

## 🏗️ Project Structure

```text
Mica-OS-Pyron/
│
├── apps/                 # System and user applications
│
├── backend/              # Python backend
│   ├── main.py
│   ├── auth.py
│   ├── apps_mgr.py
│   ├── backup_mgr.py
│   ├── fs.py
│   ├── mupdate_mgr.py
│   ├── plugins_mgr.py
│   ├── python_runtime.py
│   ├── security.py
│   ├── system_ctrl.py
│   └── themes_mgr.py
│
├── data/                 # Application data
│
├── frontend/             # Desktop interface
│   ├── css/
│   ├── js/
│   ├── wallpapers/
│   └── index.html
│
├── plugins/              # Plugin system
│
├── themes/               # System themes
│
├── tools/                # Development tools
│
├── native_app.py         # Native desktop application
│
├── start.bat             # Windows launcher
├── start-browser.bat     # Browser launcher
├── run.sh                # Linux/macOS launcher
│
└── README.md
```

---

## 🛠️ Built With

Mica OS Pyron uses a combination of web and native Python technologies.

### Backend

* **Python**
* **FastAPI**
* **Uvicorn**
* **Pydantic**
* **AIOFiles**

### Native Desktop

* **PyQt6**
* **PyQt6 WebEngine**

### Security & System

* **Cryptography**
* **psutil**

### Frontend

* HTML
* CSS
* JavaScript
* Custom desktop window system
* Glassmorphism / Liquid Glass UI

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed.

Recommended:

```text
Python 3.10+
```

---

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/mica-os-pyron.git
```

```bash
cd mica-os-pyron
```

---

### 2. Install Dependencies

```bash
pip install -r backend/requirements.txt
```

---

### 3. Run Mica OS Pyron

#### Windows

```text
start.bat
```

#### Browser Mode

```text
start-browser.bat
```

#### Linux / macOS

```bash
chmod +x run.sh
./run.sh
```

---

## 🖥️ Native Application

Mica OS Pyron can also run as a native desktop application using PyQt6 and WebEngine.

The native application entry point is:

```text
native_app.py
```

This allows the web-powered operating system interface to run inside a dedicated desktop window.

---

## 🔧 Development

The project is divided into multiple independent systems.

### Backend Systems

| System          | Purpose                      |
| --------------- | ---------------------------- |
| Authentication  | User accounts and login      |
| Apps Manager    | Application management       |
| Backup Manager  | Backup functionality         |
| File System     | File operations              |
| Update Manager  | System updates               |
| Plugins Manager | Plugin support               |
| Python Runtime  | Python application execution |
| Security        | Security utilities           |
| System Control  | System-level controls        |
| Themes Manager  | Theme management             |

---

## 📱 Vision

Mica OS Pyron explores the idea of a modern, customizable operating system experience built with web technologies and Python.

The project focuses on:

* 🎨 Beautiful and experimental UI
* 🖥️ Modern desktop interactions
* 🧩 Modular applications
* 🔌 Plugin support
* 🎨 Customization
* 🔐 User accounts and security
* 🐍 Python integration
* 🌐 Web-powered desktop applications
* 💻 Native desktop support

---

## 📸 Screenshots

Screenshots and demos coming soon.

You can also explore the live version:

[Launch Mica OS Pyron](https://micaos-pyron.netlify.app/?utm_source=chatgpt.com)

---

## 🗺️ Roadmap

* [x] Modern desktop interface
* [x] Application system
* [x] User authentication
* [x] Guest Mode
* [x] Lock screen
* [x] Theme system
* [x] Plugin architecture
* [x] File explorer
* [x] Terminal
* [x] Package manager
* [x] Python environment
* [x] Native desktop application
* [ ] More third-party applications
* [ ] Expanded plugin ecosystem
* [ ] More themes and wallpapers
* [ ] Enhanced window management
* [ ] More creative tools
* [ ] Improved system updates
* [ ] Community application support

---

## 🤝 Contributing

Contributions, ideas, and improvements are welcome!

You can contribute by:

* Reporting bugs
* Improving the UI
* Creating applications
* Developing plugins
* Creating themes
* Improving documentation
* Suggesting new features

---

## 📄 License

License information coming soon.

---

<div align="center">

# Mica OS Pyron

### A modern desktop experience powered by Python and the Web.

**Built to experiment. Designed to explore.**

🌐 [Try Mica OS Pyron](https://micaos-pyron.netlify.app/?utm_source=chatgpt.com)

</div>
