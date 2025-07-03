---
title: "KX-36"
author: "@AVSC"
description: "BLDC RC Off-Road RWD Racecar"
created_at: "2025-06-9"
total time spent: "~30hrs"
---

(Fast, rugged, and 3D Printed RWD RC car with 2x Drone BLDC motors)

---

### Day 1: concept dump & sketchboard

**Time Spent:** \~4 hrs
kicked off the build w/ a lot of tea and a LOT more random ideas. brain was kinda everywhere today.

* grabbed a notebook and just started dumping whatever ideas came to mind. i knew i wanted 2 axles and rear-wheel-drive. that’s it.
* came up w/ this dumb but cool idea — 2x 1000KV drone motors feeding into a single GT2 pulley. totally overkill. totally doing it.
* most ppl online use PVC or alu for the frame, but i’m going all in on 3D print. like, every single part. even washers if possible.
* thought of a rear pod that swings to fake suspension vibes, while the front just stays stiff w/ steering.
* scribbled a BOM for parts: motors, pulleys, MG996R, ESCs, bearings. if it’s in the junk bin, it’s fair game.

set myself a challenge — every single part must fit on a 220x220 bed. no glue. no slicing into 20 parts. no nonsense.

---

### Day 2: rear drivetrain module

**Time Spent:** \~5 hrs
onshape the GOAT (die fusion360) . built most of the back end.

* put 2 A2212 motors mirrored and modeled a GT2 pulley system that feeds torque into a single 5mm axle.
* made hex wheel hubs that press-fit onto that same axle — no diff, both wheels spin same speed.
* made a custom bracket that holds both motors tight w/ cutouts and belt tension slots.
* added ribs n’ walls to the pulley block so it doesn’t flex when the car's ripping around.
* everything either snaps in or bolts together. no glue, no epoxy, no drama. full module is swappable like drone arms.

spent too long on belt tension — finally just threw in a top roller and extended the flanges. it’s holding fine now.


![result (3)](https://github.com/user-attachments/assets/a50f814c-fd8d-43a4-acfa-eb951c283b73)


---

### Day 3: front steering mess

**Time Spent:** \~4 hrs
ugh steering. didn’t wanna do this but had to.

* made some chunky knuckles w/ pivot arms and mini stub axles for the front wheels.
* linked up the MG996R servo to a drag link + tie rod. it’s janky but it works.
* kinda followed ackermann steering stuff? not too serious. close enough for dirt.
* servo sits in a nice little pocket above the axle — hidden and outta the way.
* front axle bolts to the spine w/ 4 screws. fast to swap if anything breaks.

<img width="258" alt="image" src="https://github.com/user-attachments/assets/f94675bc-2f0e-417c-8908-74cfc07c1084" />


![result](https://github.com/user-attachments/assets/fc7fc6d5-d0d8-4a9b-836b-8b93634e4e9f)


![result (1)](https://github.com/user-attachments/assets/53ed5e73-2a87-48c0-a988-a94339fa308d)



---

### Day 4: chassis spine

**Time Spent:** \~5 hrs
made the skeleton. simple, strong, modular.

* the chassis is just a long rail. every part bolts on like train cars.
* added slots for everything: front axle, rear pod pivot, ESCs, battery tray, RX.
* made zip tie guides and wire tunnels in the side walls — zero spaghetti cables.
* tried to keep everything symmetrical so future changes don’t break stuff.
* split the whole spine into 3 printable sections (<200mm). added pegs so it snaps together clean.

<img width="234" alt="image" src="https://github.com/user-attachments/assets/a40a9300-58cc-4376-9946-bc8eca5c74b6" />


every part’s mounted using M3/4 nuts and screws. they’re everywhere. everything locks down tight now.


![result (2)](https://github.com/user-attachments/assets/2d0ad96f-1a8d-4dd9-a2d5-14fb10ad0f05)


---

### Day 5: rear articulation test

**Time Spent:** \~4 hrs
started playing around w/ suspension ideas.

* rear pod is now pivot-mounted. it swings under pressure like a rocker.
* added dummy arms and shock mounts w/ travel for off-road use.
* used parametric features so i can tweak angles later without redrawing.
* made pivot bushings that work w/ 3mm metal rods. tight tolerances only.
* battery tray now sits low in the frame — lowers center of gravity a bit.

rear pod kinda dangles under the car now. looks like a mix of a buggy and a moon rover.

<img width="226" alt="image" src="https://github.com/user-attachments/assets/fbb1905c-f931-4b3e-99e5-5e8fec702725" />


---

### Day 6: full assembly test

**Time Spent:** \~4 hrs
put everything together in cad. moment of truth.

* imported all the modules into one file — front, mid, back.
* made sure GT2 belt clears the chassis and wires don’t rub anything.
* servo angle, steering travel — checked everything. no weird clashes.
* tweaked hole sizes and added chamfers so M4 screws go in easy.
* 

  ![t725](https://github.com/user-attachments/assets/47c33c6f-9d02-44d6-bc92-043c33c67a09)


this thing fits together like LEGO. every part either slots or bolts. super satisfying.


![result (5)](https://github.com/user-attachments/assets/678b74dd-6b15-426f-8ac0-2fcc3fcbb67b)



---

### Day 7: print prep

**Time Spent:** \~4 hrs
prep day. time to get slicer-ready.

* fixed orientation for every STL so there’s less support and stronger prints.
* named files properly — no more "final\_final\_real.stl" stuff.
* double-checked tolerances using the caliper tool in cad. everything should fit.
* added pegs + markers to help line things up while assembling.
* estimated around 380g PLA/PETG total, 11-12 hrs of print time unless the bed acts up.

also made a proper BOM & wrote down readme.


![image](https://github.com/user-attachments/assets/bab96a03-8d37-48fc-a0c0-cc7710fdd6c6)


---

### status update

all cad files are final and exported. STLs are cleaned up and sitting in the print folder. now just waiting for the real-world parts to show up:

* 2x A2212 1000KV motors
* GT2 5mm pulley kit + 200mm belt
* 2x 30A ESCs + RX and TX

as soon as stuff lands, printing begins. fingers crossed it drives like a beast and doesn’t melt the first time i hit throttle.

---


