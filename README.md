
# Turbo Thales

**Turbo Thales** is a comprehensive, Python-native GUI toolkit and visual builder designed for developing advanced technical, scientific, and industrial applications—without requiring manual code development.

It provides software developers in technical, scientific, and industrial fields
with a complete and powerful resource for creating applications in data acquisition and
machine control.

---

## Key Features

- Over 40 customizable GUI components
  - Analog meters (120° to 360°)
  - Switches, potentiometers, rotary selectors, and sliders
  - 7-segment display, compass, logic analyzer, oscilloscope
  - Audio alert, timer, data logger, and more

- Visual GUI Builder
  - Drag-and-drop interface design
  - Auto-generates clean and readable Python code
  - Real-time visual preview

- Built for industrial and scientific environments
  - Compatible with embedded systems and data logging platforms
  - Ideal for diagnostics, test systems, and process control

- Professional user interface output
  - Industrial layout, scalable components
  - Clean separation of interface and logic layers

---

## Component Overview

| Component         | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| Bevel3D           | Base element usable as a background, sunken or raised                      |
| TransparentLabel  | Rotatable label in 1° steps, supports any font and color                   |
| FlashLabel        | Blinking colored text field, ideal for status indicators                   |
| SlideButton       | Slide switch with customizable label and colors                            |
| StatusIndicator   | Customizable LED-based status display, replaces checkboxes/radio buttons   |
| GlyphButton       | Button with text and optional glyph                                        |
| SelectSlide       | Slider with up to 20 detents, fully labelable                              |
| LoadingBar        | Progress bar supporting percentage or real values                          |
| Compass           | Compass display with digital readout                                       |
| MeterPanelH       | Horizontal panel meter with LED indicators and label options               |
| MeterPanelV       | Vertical panel meter with digital readout and customizable appearance      |
| Meter120          | 120° panel meter with digital display and drag pointer                     |
| Meter180          | 180° panel meter with digital display and drag pointer                     |
| Meter270          | 270° panel meter with digital display                                       |
| Meter360          | 360° dual-scale panel meter with two pointers                              |
| LogView           | Real-time log viewer, ideal for event logging and diagnostics              |
| BoxLine           | Binary bit display (horizontal/vertical), reversible bit order             |
| ArrowSpin         | 360° directional arrow indicator                                            |
| Logicana          | Digital logic analyzer with channel control                                 |
| Oscillo           | Fully functional oscilloscope component                                     |
| xyGraph           | Real-time capable measurement graph                                         |
| StatChart         | Configurable statistical chart component                                   |
| SmartTimer        | Multi-channel timer control                                                 |
| PlaySnd           | Program-controlled audio playback                                           |
| Iconize           | Minimizes program to taskbar or hides it completely                        |
| FormLang          | Multilingual support for widget text                                        |
| DetSlider         | Detented slider with infinite detents and orientation options              |
| Slider            | Smooth slider with configurable start and end values                       |
| Selector270       | Rotary switch with infinite detents                                         |
| Poti270           | 270° potentiometer with custom scale                                        |
| Poti10K           | Dual-range potentiometer (270° and 3600° knobs)                             |
| AlphaBar          | On-screen keyboard for systems without hardware keyboard                   |
| SevSegSpin        | Thumbwheel switch with 7-segment display                                    |
| SevSeg            | Seven-segment display with controllable LEDs                               |
| FullSevSeg        | Fully customizable seven-segment display                                    |
| DigiTime          | Digital time display with full color control                                |
| MagicEye          | Bar graph suitable for spectrum display                                     |


---

## Example: Creating an Instrument Panel

```python
import tkinter as tk
from thales import Meter270

root = tk.Tk()
root.geometry("800x600")

meter_widget = Meter270(root, style="rect")
meter_widget.pack()

meter_widget.set_value(59.34)

root.mainloop()
```

---

## Turbo Thales

Turbo Thales is the official visual GUI builder for the Thales component library.

Features:
- No-code interface design
- Auto-generated Python UI code
- Integrated preview
- Project save/load support

Intended for:
- Laboratory and testing stations
- Embedded HMIs
- Control and diagnostics dashboards

To obtain a commercial license, please contact us at [info@infrontechnologies.com](mailto:info@infrontechnologies.com).

---

## Community and Support

- Report issues: [GitHub Issues](https://github.com/yourname/turbo-thales/issues)
- License inquiries and support: [info@infrontechnologies.com](mailto:info@infrontechnologies.com)

---

## Maintainer

Turbo Thales is developed and maintained by Infron Technologies.

Designed to empower engineers, researchers, and industrial developers with efficient Python-native GUI solution.
