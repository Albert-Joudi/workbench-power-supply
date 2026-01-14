# workbench-power-supply

## Overview
This project is a **workbench AC to DC power supply** built as part of a college **Electronic Fabrication** course. The power supply converts **AC power** into multiple fixed **DC output voltages** and is designed for safely powering and testing low-voltage electronics projects.

The goal of this project was to develop hands-on skills in **soldering**, **electronic assembly**, **mechanical fabrication**, and **lab testing procedures**.

---

## Project Media
<p align="center">
  <img src="media/power_supply_front.png" height="200" />
  <img src="media/power_supply_inside.png" height="200" />
</p>
▶ Watch the power supply output voltage test: https://youtube.com/shorts/83OS70JJXFI?si=V1skPdoeHpECwpiW

---

## Features
- Converts AC to DC
- Fixed DC output voltages:
  - **5V**
  - **12V**
  - **17V**
- Multiple output terminals on the top panel
  - Different voltage outputs are achieved by selecting different terminal combinations
- **USB port providing 5V output**
  - Can directly power devices such as an Arduino
- **On/Off power switch**
- **Status LED** indicating when the power supply is powered on
- Fully enclosed case for electrical safety

---

## Output Configuration
- The power supply provides multiple fixed voltage outputs using a shared terminal system.
- There is no single dedicated ground terminal.
- Output voltage is selected by changing which terminals are used for **VCC** and **GND**.
- This design allows:
  - 5V, 12V, or 17V output depending on terminal selection
- USB port provides a regulated **5V DC output** independent of terminal selection.

---

## Hardware Construction
- PCB and electronic components were provided by the college
- Assembly process included:
  - Through-hole soldering of all electronic components
  - Mechanical drilling of the enclosure top panel
  - Installation of output terminals
  - Mounting the assembled PCB inside the case

---

## Mechanical Design
- Custom drill hole layout was created for:
  - Output terminals
  - Status LED
- Drill layout file is included in the repository for reference
- Enclosure design prioritizes:
  - Electrical safety
  - Clear access to output terminals
  - Secure mounting of the PCB

---

## Testing & Verification
- Final assembled power supply was tested using a **digital multimeter**
- Verified:
  - Correct DC voltage levels at the output terminals
  - Proper operation of the power switch
  - Status LED functionality
- Testing process is documented with photos and video in the `media` folder
- All testing followed standard **lab safety procedures**

---

## Skills Demonstrated
- Through-hole soldering
- Power supply testing and verification
