# RPEN V2 – Next-Gen Connected Pen 🖊️⚡

RPEN V2 (Remote Pen & Air Pen) is the upgraded version of the initial DEEP project developed at ESEO.  
This new version uses a more powerful microcontroller and high-performance components to provide smoother, faster, and more precise remote writing.  

## Planned Features

- **Remote Writing:** Improved motion sensing with next-gen IMU for higher precision.
- **Interactive Modes:** Writing, calibration, and erase with better responsiveness.
- **Customization:** Enhanced size/color management and smoother drawing.
- **User Feedback:** Smarter RGB/haptic feedback for real-time interaction.
- **Wireless Communication:** More stable and low-latency than the previous version.

## Technical Overview

- **Hardware:**  
  - Stronger microcontroller (exact model TBD).  
  - More advanced motion sensor (successor to MPU6050).  
  - Improved feedback system (RGB LEDs, haptics).  
  - TFT screen with optimized interface.  

- **Software:**  
  - Optimized Bluetooth (or alternative) data transmission.  
  - Better noise filtering and frame processing.  
  - Improved algorithms for smoother pen-to-screen interaction.  

## Roadmap

- [ ] Select final microcontroller and components.  
- [ ] Prototype transmitter & receiver.  
- [ ] Implement improved wireless protocol.  
- [ ] Optimize feedback and user experience.  

## Project Structure

- **Transmitter** → Captures motion, user input, and sends data wirelessly.  
- **Receiver** → Receives data frames and renders drawings on a TFT screen.  

Both modules are stored in their own repositories and included here as submodules for clean versioning.

## Cloning the Repository

Since this project uses **Git submodules**, make sure to clone it with:

```bash
git clone https://github.com/Kevin-Pottier/RPEN_V2.git
cd RPEN_V2
git submodule update --init --recursive
```

To get the last versions of Transmitter and Receiver separately, you can pull the latest changes into RPEN_V2 with: 
```bash
git submodule update --remote --merge
```

## Developer

- **Kévin Pottier** – [GitHub](https://github.com/Kevin-Pottier) | kevin.pottier@reseau.eseo.fr  

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.
