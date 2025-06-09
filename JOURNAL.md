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
Started with tea and chaos. Ideas everywhere.

* Took out my notebook and dumped every rough sketch and half-baked idea from my brain — 2-axle, RWD layout only.
* Dual 1000KV A2212 motors on a shared GT2 pulley? Seemed overkill — so obviously, I went with it.
* Most online builds go PVC or aluminum; I decided to ditch that route and go full plastic — everything 3D printed, down to the last washer if I can help it.
* Thought up an articulated rear pod setup that can pivot, giving some faux-suspension. Chassis up front remains a fixed spine with steering.
* Jotted down a barebones BOM: motors, pulleys, 3D printed couplers, MG996R servo, ESCs, bearings — basically whatever was still lying around in my parts bin.

📌 Challenge for the week: everything must be printable on a 220x220 bed without hacks or multi-part gluing. Game on.

---

### 📅 Day 2: Rear Drive Module — Core Drivetrain

**Time Spent:** \~5 hrs
Fusion 360 in full throttle.

* Modeled the two A2212s mirrored so that both feed power into a common GT2 pulley sitting on a central 5mm rear axle.
* Designed custom hex wheel hubs that slide onto the same axle — no differential, both wheels spin together.
* Built a dual-motor bracket with motor-shaped cutouts for perfect fitment and integrated belt tensioning slots.
* Added reinforcement ribs to the pulley holder to prevent flex and cracking during torque surges.
* Every component snaps or bolts in. No glue. No nonsense. Rear pod is its own module — hot-swappable like a racing drone arm.

🧠 Spent too long figuring out how to keep belt tension steady under axle twist. Settled on an upper roller system and wider belt flanges. Feels robust now.

---

### 📅 Day 3: Front Axle Steering — Simplified Ackermann

**Time Spent:** \~4 hrs
Steering — the one thing I didn't want to deal with, but had to.

* Created basic steering knuckles with pivot arms and short stub axles for the front wheels.
* MG996R servo directly links to a drag link → tie rod setup — clean, minimal, enough play to avoid binding.
* Tried to respect Ackermann geometry, but not obsessively. It’s an off-roader, not an F1 car. Close enough works.
* Servo is mounted in a recessed cavity just above the axle for protection and wire clearance.
* The front axle mounts to the chassis using a four-point bolt system for tool-free replacement.

🛞 The best part? Knuckles designed for tool-less wheel swap. No more fiddling with microscopic hex screws in sand.

---

### 📅 Day 4: Chassis Spine & Mounting Layout

**Time Spent:** \~5 hrs
Built the skeleton — and it’s modular.

* The chassis is a long, rail-based spine. All components slide and bolt onto it like train cars on a track.
* Built in mount interfaces for: front steering axle, rear pod pivot, battery tray underneath, ESCs, and RX unit.
* Routed zip tie guides, wire tunnels, and ventilation directly into the side walls — no spaghetti wiring here.
* Kept the entire layout symmetrical and modular, so I can redesign just one module without touching the rest.
* Divided the frame into 3 printable pieces, each <200mm, with tabs and pegs for clean snap-fit and alignment.

🎯 Printability, repairability, airflow, and tool access — all baked in by design, not as afterthoughts.

---

### 📅 Day 5: Suspension Mock & Rear Articulation

**Time Spent:** \~4 hrs
Time to make it *bounce*.

* Mounted the rear drive pod to the main spine using a central pivot — it swings under load like a rocker arm.
* Added placeholders for suspension arms, with shock-ready slots and enough travel for chunky terrain.
* Used parametric modeling for the shock mounts — lets me change angles and lengths without redrawing the model.
* Designed low-friction pivot bushings using standard 3mm metal rods. No fancy parts, just smart tolerances.
* Battery tray now partially sinks into the chassis base, keeping center of gravity low and stable.

🤘 The rear pod now kind of hangs under the car — gives it a vibe somewhere between Baja buggy and hover tank.

---

### 📅 Day 6: Full Assembly & Clash Check

**Time Spent:** \~4 hrs
Time to bolt it all together in CAD.

* Imported all modules — front, rear, middle — into a master assembly file to check geometry, fit, and clearance.
* Ensured GT2 belt passes cleanly under chassis without snagging, and that motor wires don’t tangle or rub.
* Verified servo horn angles and steering clearance across full travel. No binds, no weird overlaps.
* Refined a few part tolerances, and added thread-start chamfers on every screw hole — no cross-threading nightmares.
* Created a basic tire model with knobby tread just to visualize the final look and get hyped.

🧩 Honestly feels like building with LEGO Technic — everything slots, clicks, or bolts. Can’t wait to print.

---

### 📅 Day 7: Print Prep & BOM Review

**Time Spent:** \~4 hrs
Pre-flight check before the print storm begins.

* Carefully oriented every STL for minimal supports, stronger layer lines, and easier cleanup.
* Named every part version clearly: no `final_final_v6_real_this_time.stl` garbage.
* Rechecked part tolerances by digitally simulating fit using the caliper tool in Fusion.
* Added pegs, keys, and markers for straight, idiot-proof assembly during the print phase.
* Final filament estimate: \~380g of PLA, roughly 11-12 hours print time, give or take failed first layers.

🧾 BOM spreadsheet now includes part name, weight, print time, number of parts, and assembly notes. OCD achieved.

---

### ✅ Status Update:

All CAD files are finalized, clean, and exported. STL folder is locked and ready for slicing. Currently waiting for the real-world bits to show up:

* 2x 1000KV A2212 BLDC Motors
* GT2 5mm Pulley + 200mm Belt Kit
* 2x 30A ESCs + Radio Receiver

Once they land, the print marathon begins. Let’s see if this thing screams or melts.

---

