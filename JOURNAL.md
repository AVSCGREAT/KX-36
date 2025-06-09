---
title: "KX-36"
author: "@AVSC"
description: "BLDC RC Off-Road RWD Racecar"
created_at: "2025-06-9"
total time spent: "~30hrs"
---

(Fast, rugged, and 3D Printed RWD RC car with 2x Drone BLDC motors)

---

### 📅 Day 1: Concept Dump & Sketchboard

**Time Spent:** \~4 hrs
Started with tea and chaos.

* Scratched out early sketches of a 2-axle, rear-wheel drive RC platform.
* Dual A2212 BLDC motors directly drive a shared GT2 pulley on a central axle — no differential, just brute force.
* Noticed most DIY builds use metal or PVC. I'm skipping all that — 100% 3D printed, including motor mounts and pulley adapters.
* Concept: Articulated rear pod with suspension, fixed spine chassis up front, servo-based front steering.
* Listed initial BOM: motors, GT2 belt/pulleys, ESCs, bearings, 3D printed couplers.

📌 Goal set: everything printable on a 220x220mm bed. Let’s see.

---

### 📅 Day 2: Rear Drive Module — Core Drivetrain

**Time Spent:** \~5 hrs
Fusion 360 time.

* Modeled both A2212 motors mirrored, with shafts feeding into a central GT2 pulley on a 5mm axle.
* Rear wheels designed to mount via printable hex hubs to the same axle.
* Created a rigid dual-motor bracket with snap-fit motor slots and belt tensioning guides.
* Reinforced pulley bracket with ribs and bolt holes for structural integrity.
* Everything’s modular — can unbolt the motors or pulley without ripping the whole rear pod apart.

🧠 Problem of the day: how to keep belt tension constant with slight axle flex? Solved with belt guide rollers and oversized flange.

---

### 📅 Day 3: Front Axle Steering — Simplified Ackermann

**Time Spent:** \~4 hrs
Steering isn’t fun — but we need it.

* Designed front steering knuckles with 3D printed pivot arms and stub axles.
* MG996R servo modeled with direct connection to drag link → tie rod → knuckles.
* Ackermann geometry “close enough” for an off-roader, not aiming for race precision.
* Servo mount sits in a lowered tray on the front axle. Clean and accessible.
* Bolt-down system for axle-to-chassis for easy replacement.

🛞 Designed knuckles so wheels can be swapped in seconds. Always hated fiddly hardware.

---

### 📅 Day 4: Chassis Spine & Mounting Layout

**Time Spent:** \~5 hrs
Made the “skeleton” today.

* Main chassis: long spine with slotted rails for modules to slide in and lock.
* Created mount points for:

  * Front axle
  * Rear drive pod (via pivot joint)
  * Battery tray (under-top mount)
  * ESCs + Receiver (hidden below sandwich plate)
* Modeled cable tunnels and zip tie guides directly into the chassis walls.
* Left enough room between rails for airflow and hands.

🎯 Everything fits into 3 segments under 200mm each, print-friendly and repairable.

---

### 📅 Day 5: Suspension Mock & Rear Articulation

**Time Spent:** \~4 hrs
Getting fancy.

* Rear pod now mounted via single pivot shaft to allow articulation.
* Added 2 suspension arms (shock-ready) — simulated flex under terrain stress.
* Used parametric slots so I can later tweak spring travel and damper mounts.
* Print-ready bushings for pivot points modeled using standard 3mm rods.
* Lowered the CG by sinking battery tray into the chassis spine.

🤘 Rear pod kinda "floats" under the spine now. Feels cool.

---

### 📅 Day 6: Full Assembly & Clash Check

**Time Spent:** \~4 hrs
Time to bring all parts together.

* Imported front axle, rear pod, chassis, and electronics into one master assembly.
* Checked:

  * GT2 belt clearance under chassis
  * Motor cable exits and interference
  * Battery access slot
  * Servo horn and wheel angle limits
* Adjusted a few tolerances and swapped all M3 screw holes to include thread starts.
* Modeled test wheel with tread just to visualize stance.

🧩 Feels like LEGO. Surprisingly compact.

---

### 📅 Day 7: Print Prep & BOM Review

**Time Spent:** \~4 hrs
The final touch before print marathon.

* Oriented every part for printing — no supports wherever possible.
* Labeled STL exports clearly: `rear_mount_L_v2.stl`, `belt_cage_final.stl`, etc.
* Verified nut traps and part fitting by measuring in CAD.
* Added pegs + alignment keys to aid in straight assembly.
* Estimated filament use: \~380g PLA, \~12 hrs total print time for all parts.

🧾 BOM updated with print time, part weight, assembly order.

---

### ✅ Status Update:

All 3D models locked and STL files exported. Just waiting on:

* 2x 1000KV A2212 BLDC Motors
* GT2 pulley + belt set
* ESCs + Radio Receiver

Once they arrive — the print-and-build phase begins.

---

Would you like me to also make a matching “Build Journal” template (7-day format) once you begin the printing and assembly?





