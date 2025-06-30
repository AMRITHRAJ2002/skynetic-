# 🚀 [SKYNETIC]

<div align="center">
<div style="background-color: #000; padding: 20px; border-radius: 12px; display: inline-block;">
  <img src="./logo.jpg" alt="Ecocee Logo" width="120" height="120" />
</div>

  
  ### Internship Project at [Ecocee](https://ecocee.in)
  
  [![Website](https://img.shields.io/badge/Website-ecocee.in-blue?style=for-the-badge&logo=globe)](https://ecocee.in)
  [![Email](https://img.shields.io/badge/Contact-info%40ecocee.in-red?style=for-the-badge&logo=gmail)](mailto:info@ecocee.in)
  
</div>

---

## 📋 Project Overview

**Batch:** [Your Batch Summer 2025]  
**Team Number:** [Team 03]  
**Internship Position:** [Embedded Developer Intern]  
**Duration:** [12-06-2025 - 30-06-2025]

### 👥 Team Members
| Name | Role | Email | LinkedIn |
|------|------|-------|----------|
| [AMRITHRAJ M M] | [Team Lead/Developer] | [amruthrajmurali1441@gmail.com] | [https://www.linkedin.com/in/amrithraj-m-m-512780338?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app] |
| [SHREYAS K P] | [Developer/Researcher] | [Shreyas5710kp@gmail.com] | [https://www.linkedin.com/in/shreyas-k-p-5016a432b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app] |

> **Note:** Add or remove rows as needed based on your team size

### 🎯 Description
[*Skynetic* is a robotic sensing project where ESP32-S2-WROVER is used to identify physical interactions with a robot — distinguishing between soft touches and harsh slaps. Flex sensors and MS5837 pressure sensors detect and measure the force, while LEDs provide immediate feedback. This project bridges human emotion with machine perception.]

---

## 🔧 Technical Specifications

### **For Embedded Developer Intern Projects:**
- **Microcontroller/Platform:** ESP32.
- **Programming Languages:** C/C++.
- **Communication Protocols:** I2C, SPI, UART, WiFi, Bluetooth, etc.
- **Sensors/Components:** [ESP32,FLEX SENSOR,PRESSURE SENSOR,MUX]
- **Development Environment:** Arduino IDE.

---

## ⚙️ Project Working
Skynetic's touch sensing capabilities are driven by a precise step-by-step process, allowing the system to interpret physical interactions and respond dynamically.
Touch Input
A touch or slap is applied to the sensor array.
Sensor Data
Flex and pressure sensors convert physical contact into electrical signals.
ESP32 Processing
The ESP32 reads and analyzes sensor data against predefined thresholds.
LED Output
Based on intensity: Soft touch = Green LED Hard slap = Red LED

### Architecture Overview
[Provide a high-level overview of how your project works. You can include diagrams, flowcharts, or system architecture images here.]

### Key Components
1. **ESP 32** [The ESP32 reads and analyzes sensor data against predefined thresholds.]
2. **FLEX SENSOR:** [Flex and pressure sensors convert physical contact into electrical signals]
3. **PRESSURE SENSOR:** [A touch or slap is applied to the sensor array]

### Algorithm/Logic Flow
```
 Skynetic Algorithm (Touch & Slap Detection)
Start system
 • Set up pins and turn off LEDs.

Read sensors
 • Read flex sensor → flexValue
 • Read pressure sensor → pressureValue

Map pressure
 • Convert pressure to mbar scale.

Check interaction
 • If flex is bent:
  – If pressure > 1000 → Slap → Red LED ON
  – Else if pressure > 300 → Touch → Green LED ON
  – Else → Both LEDs OFF
 • Else → Both LEDs OFF

RepeatStep 1: [Description]
   ↓
Step 2: [Description]
   ↓
Step 3: [Description]
   ↓
Result: [Final output/outcome]
```

---

## 🚀 Applications & Use Cases

### Primary Applications
- Enhancing *Human-Robot Interaction (HRI)*
- Wearable *assistive technologies*
- *Security bots* that respond to aggressive behavior

### Future Scope
- Add vibration or haptic feedback
- Wireless communication via WiFi/Bluetooth
- Real-time data visualization
- Gesture classification using ML

---

## 📱 Demo & Results

### Screenshots/Images
> To be updated upon circuit test and result documentation

### Performance Metrics
| Metric | Value |
|--------|-------|
| Flex Detection Threshold | ~1800 |
| Pressure Range | 300–1000+ mbar |
| Reaction Time | ~200 ms |

---

## 🛠️ Installation & Setup

### Prerequisites
bash
- Arduino IDE
- ESP32 Board installed
- Required Libraries: Wire.h



### Installation Steps
```bash
bash
git clone https://github.com/Shreyas-k-p/Skynetic.git
cd Skynetic
Open .ino file in Arduino IDE
Upload to ESP32-S2-WROVER
# Clone the repository
git clone [your-repo-link]

# Navigate to project directory
cd [project-name]

# Install dependencies
pip install -r requirements.txt

# [Additional setup steps]
```

### Usage
```bash
bash
Connect sensors to ESP32
Power the system
Touch or slap to see LED response


```

---

## 📊 Project Structure
```
Skynetic/
├── code/                 # Arduino IDE code
├── docs/                 # Block & Circuit Diagrams
├── presentation/         # PPT
├── README.md             # Overview and Summary


---

## 🎓 Learning Outcomes

### Technical Skills Gained
- [Skill 1 - e.g., Machine Learning model development]
- [Skill 2 - e.g., Embedded programming]
- [Skill 3 - e.g., Data analysis and visualization]

### Tools & Technologies Mastered
- [Tool 1]
- [Tool 2]
- [Tool 3]

---

## 🤝 Acknowledgments

Special thanks to the **Ecocee team** for providing guidance and support throughout this internship project.

**Mentor:** [SREERAJ V RAJESH]  
**Team Number:** [Team #03]  
**Team Size:** [02]

### 👨‍💼 Team Contributions
| Team Member | Primary Contributions |
|-------------|------------------------|
| Shreyas K P | Coding, Circuit Design, Documentation, Presentation|
| Amrithraj M M | Component Wiring, Testing, Presentation, Documentation |

---

## 📞 Contact

**Company:** Ecocee  
**Website:** [ecocee.in](https://ecocee.in)  
**Email:** [info@ecocee.in](mailto:info@ecocee.in)

### 👥 Team Contacts
| Team Member | Email | LinkedIn | GitHub |
|-------------|-------|----------|--------|
| [SHREYAS KP] | [Shreyas5710kp@gmail.com] | [https://www.linkedin.com/in/shreyas-k-p-5016a432b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app] | [GitHub Profile] |
| [AMRITHRAJ M M] | [amruthrajmurali1441@gmail.com] | [https://www.linkedin.com/in/amrithraj-m-m-512780338?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app] | [https://github.com/AMRITHRAJ2002] |

---

<div align="center">
  
  **Made with ❤️ during internship at Ecocee**
  
  ⭐ **Star this repo if you found it helpful!** ⭐
  
</div>

---

## 📄 License

This project is developed as part of an internship program at Ecocee. Please refer to the company's guidelines for usage and distribution.

[Optional: Add specific license if applicable]
