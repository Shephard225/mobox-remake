# Mobox-Remake

**Mobox-Remake** is a continuation and remake of the original **Mobox** emulator.  
The project was created to continue the development of Mobox, as the original author abandoned the project.

---

## What is Mobox

Mobox is an emulator project that allows running Windows x86 applications and games on Android devices via **Termux**, using **Box64/Box86** and compatibility through **Wine**.  
- Supports Vulkan rendering through Mesa VirGL, enabling graphically demanding games to run.  
- Designed for modern Android devices, especially high-performance Snapdragon chips, to ensure stability and performance.  
- Mobox became popular for running Windows games (Steam, .exe applications) on mobile, offering an alternative to cloud gaming or less capable solutions.

---

## Why Mobox-Remake

- The original Mobox repository was archived and development stopped.  
- I decided to continue the project, fix bugs, and add new features so the community can keep using and improving this emulator.  

**Main goals:**  
- Fix bugs from the original version  
- Optimize performance  
- Add new features (configurations, UI improvements, dynarec settings, etc.)  
- Improve documentation and user support

---

## Installation

> General installation steps based on the original Mobox. Exact steps may vary depending on the remake version.

1. Install **Termux** and **Termux-X11** on your Android device.  
2. Download and install **Input Bridge** (or Xinput Bridge) for input control.  
3. In Termux, run:
   ```bash
   curl -s -o ~/install_mobox_remake.sh <link_to_install_script> && bash ~/install_mobox_remake.sh
