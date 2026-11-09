![Lucas Tsui — Code, circuits, curiosity](assets/banner.svg)

I build small systems to understand bigger ideas. My projects connect **embedded code, electronics, and simulation**—from FPGA timing logic to camera-guided robotics.

### On the workbench

<table>
<tr>
<td width="50%"><a href="https://github.com/2226442613/nathacks-2026-project"><img src="assets/robotics.svg" width="100%" alt="BioGuard: camera-guided cleaning robot prototype. Python, OpenCV, ESP32." /></a></td>
<td width="50%"><a href="https://github.com/2226442613/FPGA-Reaction-Timer-Game"><img src="assets/logic.svg" width="100%" alt="FPGA Reaction Timer: state machines and timing in VHDL." /></a></td>
</tr>
<tr>
<td><a href="https://github.com/2226442613/RLC-Circuit-Analyzer"><img src="assets/circuits.svg" width="100%" alt="RLC Analyzer: circuit frequency and step-response simulation in Python." /></a></td>
<td><a href="https://github.com/2226442613/LensLab"><img src="assets/optics.svg" width="100%" alt="LensLab: exposure and field-of-view simulation in C++." /></a></td>
</tr>
</table>

More experiments: [**MorsePulse**](https://github.com/2226442613/MorsePulse) · [**ARM Assembly Mini Toolkit**](https://github.com/2226442613/ARM-Assembly-Mini-Toolkit) · [**Temperature Monitor**](https://github.com/2226442613/Embedded-Temperature-Monitor-Project)

### My toolkit

**Languages** &nbsp; C · C++ · Python · VHDL · ARM Assembly  
**Hardware & control** &nbsp; ESP32 · Arduino · FPGA · Sensor interfaces  
**Vision & software** &nbsp; OpenCV · Flask · Git · GitHub

### From an idea to something that works

**Build → measure → understand → improve.**

I learn through experiments, keep the code readable, and document the difference between a working simulation and a tested physical system.


### Project notebook

![Observe, model, build, verify: my engineering notebook](assets/notebook.svg)

The questions behind the projects matter as much as the code:

| Question | Where I explore it |
| :--- | :--- |
| How can a robot know where it is? | Camera calibration, ArUco tracking, and feedback in **BioGuard** |
| How do you make timing predictable? | Finite-state machines and millisecond timing in the **FPGA Reaction Timer** |
| How does a circuit respond to change? | Frequency and step responses in the **RLC Circuit Analyzer** |
| What connects camera settings to an image? | Exposure and field of view in **LensLab** |

### In focus · BioGuard

<a href="https://github.com/2226442613/nathacks-2026-project">
  <img src="https://raw.githubusercontent.com/2226442613/nathacks-2026-project/main/assets/bioguard-prototype.jpg" width="520" alt="BioGuard cleaning robot prototype built for natHacks 2026" />
</a>

**A camera-guided cleaning robot prototype for natHacks 2026.**

A fixed camera feeds a Python vision pipeline. The computer tracks the robot and plans movements; an ESP32 handles movement commands and cleaning presets. A Flask dashboard brings the camera view and task progress together.

**The interesting part:** connecting perception, coordinates, communication, and physical motion in one system.

This is a prototype with simulation and selected physical tests; a complete physical cleaning workflow has not yet been verified.

[Read the project story →](https://github.com/2226442613/nathacks-2026-project#system-architecture) &nbsp; [Explore the vision code →](https://github.com/2226442613/nathacks-2026-project/tree/main/vision)

### Pick a starting point

<table>
<tr>
<td width="33%" valign="top">
<b>Start close to the hardware</b><br/><br/>
Explore memory, sensor readings, and control logic.<br/><br/>
<a href="https://github.com/2226442613/ARM-Assembly-Mini-Toolkit">ARM Assembly Mini Toolkit →</a><br/>
<a href="https://github.com/2226442613/Embedded-Temperature-Monitor-Project">Temperature Monitor →</a>
</td>
<td width="33%" valign="top">
<b>Make the invisible visible</b><br/><br/>
Turn circuit behavior, light, and signals into something you can inspect.<br/><br/>
<a href="https://github.com/2226442613/RLC-Circuit-Analyzer">RLC Circuit Analyzer →</a><br/>
<a href="https://github.com/2226442613/LensLab">LensLab →</a>
</td>
<td width="33%" valign="top">
<b>Follow a system over time</b><br/><br/>
Explore timing, state transitions, and feedback.<br/><br/>
<a href="https://github.com/2226442613/FPGA-Reaction-Timer-Game">FPGA Reaction Timer →</a><br/>
<a href="https://github.com/2226442613/MorsePulse">MorsePulse →</a>
</td>
</tr>
</table>

### Notes behind the builds

- **Small experiments first.** Isolate one behavior before connecting the whole system.
- **Visible assumptions.** Keep calibration, timing, and hardware requirements in the documentation.
- **Evidence over labels.** Separate simulated results, measured results, and unfinished work.

Have a question about a project? Open an issue in its repository so the discussion stays with the code.

---

[Explore my repositories →](https://github.com/2226442613?tab=repositories)
