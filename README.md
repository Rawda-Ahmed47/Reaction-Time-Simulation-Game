# Two-Player Reaction-Time Simulation Game ⏱️🕹️

An interactive digital logic simulation game designed in **Proteus** and physically implemented on breadboard to measure and compare reaction times between two players.

## 📌 Features
- **Two-Player Latency Testing:** Measures individual reaction speed upon signal activation.
- **Clock & Decoding Logic:** Generates timing pulses via a 555 timer, driving 7490 decade counters and 7447 BCD-to-7-segment decoders.
- **Winner Latching:** Employs JK Flip-Flops to instantly freeze the counter and latch the winning player's state.

## 📸 Circuit Implementation & Demo

### Hardware Implementation vs Proteus Schematic
| Physical Hardware Circuit | Proteus Schematic Diagram |
| :---: | :---: |
| ![Hardware Implementation](image/hardware_image.png) | ![Proteus Schematic](image/proteus_image.png) |

---

### 🎥 Live Video Demonstration
Watch the live demonstration video directly in the project files:  
👉 **[Click here to watch the Video Demo](image/demo.mp4)**

## 🛠️ Hardware Components
- **555 Timer IC** (Clock Pulse Generator)
- **7490 Decade Counters**
- **7447 BCD-to-7-Segment Decoders**
- **JK Flip-Flops** (State retention & latch logic)
- **7-Segment Displays, LEDs, Push Buttons & Resistors**

## 🚀 How to Run Simulation
1. Install **Proteus Design Suite**.
2. Open the `ROOT.DSN` file to launch and test the simulation interactively.
