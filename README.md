# Clou_Stan App


## Important ⚠️
<@&1421453148987330710> <@&1311670831239270451> 

**Update 0.2**    

1. **Clou_Stan_Land** (Completed ✅)
2. **Clou_Stan Auth API**  (Completed ✅)
3. **Clou_Stan App** (Awaiting❌)
4. **Misty App** (Awaiting❌)
5. **Clou_AI & Related Services** (Partial Operation ⚠️)
6. **Dora Pilot** (Awaiting❌)
7. **Installation and Setup of Dora UI (Insiders 0.21)** (Completed ✅)
8   **Setup of Lumin Robotics Devices (Insiders 0.2.3)** (Completed ✅)

*This post may update without notice.  
Last Updated: Oct 6*



## Status: In Development.

## Vision

**Clou_Stan App** is a next-generation Minecraft launcher built from the ground up with [Tauri](https://tauri.app/). Our goal is to provide a sleek, modern, and highly performant user experience by leveraging web technologies for the frontend and Rust for the backend.

## Project Overview

Clou_Stan App is **not a fork** of any existing launcher—it's a fresh project designed to reimagine what a Minecraft launcher can be. By utilizing Tauri, we deliver native-like performance, advanced security, and seamless cross-platform support.

- **Frontend**: Built with **React**, **TypeScript**, and **Tailwind CSS**, providing a beautiful and responsive user interface.
- **Backend**: Powered by **Rust** via Tauri, ensuring speed, safety, and reliability.
- **Architecture**: Pure Tauri, with no legacy code or dependencies from Prism Launcher or other projects.

## Technology Stack

- **Framework:** [Tauri](https://tauri.app/) (Rust backend, web-based frontend)
- **Frontend:** React, TypeScript, Tailwind CSS
- **Backend:** Rust (via Tauri)

---

## Developer Setup & API Key Requirements

### ⚠️ **IMPORTANT: Backend API Keys & Legal Notice**

Clou_Stan App relies on integration with several third-party services. Developers **must obtain and use their own API keys** for all backend services.

**You are required to:**
1. **Edit** [`src-tauri/CMakeLists.txt`](src-tauri/CMakeLists.txt) or the relevant configuration files.
2. **Replace** any placeholder API keys with your own credentials for:
   - **Microsoft (MSA)**
   - **CurseForge (Flame)**
   - **Modrinth**
3. **Do NOT use any keys you do not have explicit permission to use.**

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tschoi5675/Clou_Stan-App.git
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Configure your API keys:**
   - Add your credentials for Microsoft, CurseForge, and Modrinth in the appropriate config files.
4. **Run the app locally:**
   ```bash
   npm run tauri dev
   ```

---

## Disclaimer

- **Clou_Stan App** is an independent project and **not affiliated** with any other launcher.
- All trademarks and service marks are property of their respective owners.
- This project is offered as-is, with no warranty or guarantee of stability or support.

---

## Contributing

We welcome contributions and feedback! Please read the guidelines in [`CONTRIBUTING.md`](CONTRIBUTING.md) before opening issues or pull requests.

---

## License

Distributed under the [GPL-3.0 License](LICENSE). See `LICENSE` for more information.

---

## Credits

Special thanks to the open-source Minecraft community for inspiration and resources.
