<div align="center">

<img src="./assets/header.svg?v=4" width="100%" alt="Rohit R. Nalbuga — PCB, Embedded & RF Designer"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=3000&pause=1000&center=true&width=680&color=2F9BB3&lines=Schematic+to+fabrication-ready+in+Altium;Multi-layer%2C+controlled-impedance+PCB+design;Embedded+C+on+STM32%2C+nRF5340%2C+ESP32;One+front-end%2C+six+biopotentials;Self-studying+RF+%26+antenna+design)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=ADuetrohit&color=2f6b8a&style=for-the-badge&label=PROFILE+VIEWS)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rohit-nalbuga)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohitnalbuga2@gmail.com)
![Location](https://img.shields.io/badge/Bengaluru,%20India-2f6b8a?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/><br/>

<img src="./assets/scope.svg" width="100%" alt="Hardware signal bench — live oscilloscope"/>

</div>

<img src="./assets/divider.svg" width="100%" alt="———"/>

## 🚀 About Me

```c
board_t rohit = {
    .role      = "PCB & Embedded Systems Designer",
    .degree    = "B.Tech ExTC, expected 2027",
    .does      = "schematic -> layout -> firmware, one hand off",
    .domains   = { "RF", "biomedical", "robotics" },
    .learning  = "antenna & RF/microwave design",
};
```

- 🔩 I take PCBs from **schematic to fabrication-ready in Altium** — 2-to-6-layer, controlled-impedance boards — and write the **Embedded C** firmware that runs on them
- 🏆 My boards have been recognized at **IIT (BHU) Varanasi Technex 2026** and **IIT Bombay Techfest 2026**
- 🔭 Currently building a **behind-ear biosensing wearable** and a **6-in-1 biopotential sensor**
- 💬 Ask me about **PCB stackups, controlled impedance, or biopotential front-ends**

## ⚡ By the Numbers

<div align="center">

| 🔩 **5** | 📐 **6-layer** | ⚡ **6-in-1** | 🎯 **50 Ω / 90 Ω** | 🏅 **IIT BHU** |
|:--:|:--:|:--:|:--:|:--:|
| custom boards designed | deepest stackup | biopotential sensor | controlled impedance | Technex 2026 recognition |

</div>

## ⚙️ From Schematic to Bring-Up

> I own the whole chain — the board *and* the firmware on it.

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#12324c','primaryTextColor':'#eaf6f4','primaryBorderColor':'#2f6b8a','lineColor':'#5fd3c4','fontFamily':'monospace','fontSize':'14px'}}}%%
flowchart LR
    A([ Schematic ]) --> B([ PCB Layout ])
    B --> C([ Controlled-Z<br/>+ DFM rules ])
    C --> D([ Fabrication ])
    D --> E([ Bring-up ])
    E --> F([ Embedded C<br/>firmware ])
```

## 🛠️ Tech Arsenal

| Domain | Stack |
|:--|:--|
| **PCB & EDA** | ![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white) ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white) |
| **MCUs & Silicon** | ![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white) ![Nordic](https://img.shields.io/badge/nRF5340-00A9CE?style=for-the-badge) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white) ![Analog Devices](https://img.shields.io/badge/Analog%20Devices-00539B?style=for-the-badge) ![Renesas](https://img.shields.io/badge/Renesas-1A1A8C?style=for-the-badge) ![NXP](https://img.shields.io/badge/NXP-0A7E8C?style=for-the-badge) |
| **Firmware** | ![Embedded C](https://img.shields.io/badge/Embedded%20C-A8B9CC?style=for-the-badge&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![I2C/SPI/UART](https://img.shields.io/badge/I²C%20·%20SPI%20·%20UART-444?style=for-the-badge) |
| **Signal & RF** | ![Controlled Impedance](https://img.shields.io/badge/Controlled%20Impedance-2F4A6B?style=for-the-badge) ![RF](https://img.shields.io/badge/RF%20·%20Microwave-6B2F4A?style=for-the-badge) |

<img src="./assets/divider.svg" width="100%" alt="———"/>

## 🔬 Projects

> ⚠️ Most design files are private (in development / client work). Happy to walk through any on request.

<table>
<tr>
<td width="50%" valign="top">

**◆ Chordy** — controlled-impedance ESP32-S3 board<br/>
<sub>*4-layer · Altium · 50 Ω CPWG / 90 Ω USB, DFM to fab spec*</sub>

</td>
<td width="50%" valign="top">

**◆ VELA** — behind-ear sleep-tracking wearable<br/>
<sub>*nRF5340 · 6-layer puck + 4-layer case · optical PPG + bio-impedance*</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**◆ 6-in-1 EXG** — biopotential sensor<br/>
<sub>*TI TL074 · 2-layer · one front-end → ECG/EMG/EOG/EEG/EGG/ENG*</sub>

</td>
<td width="50%" valign="top">

**◆ VEERA** — multi-sensor IoT & robotics board<br/>
<sub>*ESP32 + Arduino UNO · 2-layer · dual motor drivers · 15+ peripherals*</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**◆ KARA_V1** — dual-MCU development board<br/>
<sub>*STM32 + ESP · 4-layer · Altium*</sub>

</td>
<td width="50%" valign="top">

**◆ AERIS** — air-quality monitor<br/>
<sub>*ESP32 · MQ sensors, calibration + filtering · Technex 2026 (IIT BHU) recognition*</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**◆ High-Speed Line Follower** — PID robot<br/>
<sub>*sensor-array line tracking · Technoxian World Cup*</sub>

</td>
<td width="50%" valign="top">

**◆ Internship builds** — Karmic Nexus<br/>
<sub>*PIC18F47K42 dev board · VC02 smart-farming · EV↔petrol switching circuit*</sub>

</td>
</tr>
</table>

## 🏆 Achievements & Roles

- 🥇 **Recognition (Hardware category)** — Technex 2026, IIT (BHU) Varanasi, for the AERIS project
- 🏅 **Circuit Mania Winner ×2** (JDCOEM, 2025 & 2026) · 2nd Place, Circuit Competition (TGPCET)
- 👥 **Technical Head**, e-Yantra Robotics Club
- 📜 Firmware Engineering — L&T EduTech

<img src="./assets/divider.svg" width="100%" alt="———"/>

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rohit-nalbuga)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohitnalbuga2@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:2f6b8a,100:0b2135&section=footer" width="100%" alt="footer"/>

</div>
