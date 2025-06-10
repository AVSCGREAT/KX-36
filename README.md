
---

# KX-36: BLDC RC Off-Road RWD Racecar
Designed and Built by AVSC

---

## Overview:

KX-36 is a rear-wheel-drive, off-road RC car powered by 2x 1000KV A2212 drone motors using a single GT2 belt system. It’s completely 3D printed – every component, from the steering knuckles to the chassis spine, was made to fit a standard 220x220mm bed. The goal? No glue, no epoxy, no weird slicing. Just bolts, nuts, and a lot of plastic.

The design is modular, overbuilt, and intentionally fun.

**Inspo/Ref. for my project**
<img width="332" alt="image" src="https://github.com/user-attachments/assets/0431e8d6-eb49-4d44-b7cb-2c4b8c5e1d01" />



---

## Specs:

Drive Type: Rear-Wheel Drive (RWD), GT2 Belt
Motors: 2x A2212 1000KV Brushless
Chassis: 3D Printed, Modular Spine
Steering: Ackermann-inspired, MG996R Servo
Suspension: Rear Pivot Pod (Passive)
Battery Mount: Low-Center Tray
Control: 2x 30A ESCs, RC RX/TX
Build Style: Snap and Screw (M3)
Printer Volume: 220x220mm compatible

---

## Bill of Materials:

### Printed Parts (PLA or PETG):

* Rear Pod and Motor Mount
* Front Steering Axle
* Chassis Spine (in 3 segments)
* Belt Cage and Guide
* Wheel Hubs and Knuckles
* Battery Tray
* Wire Management Clips
* Dummy Shocks and Arms

### Electronics & Hardware:

* 2x A2212 1000KV Motors
* 2x 30A ESCs
* 1x MG996R Servo
* 1x GT2 Pulley Kit (5mm bore, 200mm belt)
* 1x 3S LiPo Battery
* 1x RC Receiver & Transmitter
* M3 Nuts and Bolts
* 3mm Metal Rods (for pivot mounts)

---

## Development Log:

Day 1 – Concept Dump:
Started with a lot of tea and a blank notebook. Knew I wanted RWD and two axles. Came up with a wild plan to drive both rear wheels with dual drone motors using a GT2 belt. Decided everything should be 3D printed – even small things like washers if possible. Sketched a BOM based on what I already had lying around.

Day 2 – Rear Drivetrain Module:
Modeled the rear end in Fusion 360. Mirrored the two motors and added a shared GT2 pulley system onto one axle. Built a custom bracket to hold everything with proper belt tension slots. It took time, but added a top roller and larger flanges to lock it in.

Day 3 – Front Steering System:
Reluctantly tackled the front steering. Modeled chunky knuckles and stub axles. Used an MG996R servo with drag link + tie rod. It’s not super precise, but it works. Also made the front axle swappable and wheels easy to remove via pin, not tiny screws.

Day 4 – Chassis Spine:
Created a central skeleton that everything bolts onto. Designed with modularity in mind: front axle, ESCs, battery tray, all slide and screw in. Split into 3 printable sections with alignment pegs. Zip tie mounts and cable tunnels included.

Day 5 – Rear Articulation:
Experimented with suspension ideas. Made a rear pod that pivots under pressure. Added dummy shocks and swing arms for looks and a bit of travel. Used 3mm rods and tight tolerances for the pivot bushings. Lowered the battery tray to reduce CG.

Day 6 – Full Assembly in CAD:
Pulled everything together into one master file. Checked for belt clearances, steering angles, wire routes. Chamfered all screw holes for clean assembly. Even made tire mockups with treads just to get a feel.

Day 7 – Print Prep:
Reoriented all STLs for optimal printing. Cleaned up file names. Caliper-checked clearances and tolerances. Estimated \~380g PLA and 11–12 hours of total print time. Built a part-by-part BOM with print time and weights.

---

### File Structure (for organization):

KX-36

* STLs
* Fusion360 File
* Final BOM
* Render Previews
* README.txt (this file)

---

### Printing Tips:

Material: PLA or PETG
Layer Height: 0.2mm
Infill: 40–60% for strength
Supports: Minimal or none needed
Brim: Recommended for tall or thin parts
Print Volume: All fits in 220x220mm bed

---

## Project Status:

CAD work is complete. All STL files are ready and prepped.
Waiting for hardware to arrive:

* 2x A2212 1000KV Motors
* 1x GT2 Pulley Kit
* 2x 30A ESCs
* 1x Receiver and Transmitter

Printing will start as soon as parts arrive. Fingers crossed it drives and doesn’t catch fire.

---

### Future Plans:

* Replace dummy shocks with real dampers
* Add TPU tires or hybrid print rubbers
* Add telemetry (speed, temp) via Arduino or Pi
* FPV camera for POV racing
* Optional 4WD version with extra motors

---

### Tools Used:

Fusion 360 – 3D modeling
PrusaSlicer – Print prep
Onshape – Early sketches
VS Code – README editing
Blender – Optional renders

---

### Credits:

Project by AVSC (Hack Club Highway Grant project)
Big thanks to junk drawer electronics, patience, and Ctrl+Z

---

### Contact:

Want to remix, collab, or get help building your own version?
Reach out on GitHub @AVSC or through Hack Club.

---

