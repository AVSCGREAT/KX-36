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
* scribbled a BOM from leftover parts: motors, pulleys, MG996R, ESCs, bearings. if it’s in the junk bin, it’s fair game.

set myself a challenge — every single part must fit on a 220x220 bed. no glue. no slicing into 20 parts. no nonsense.

---

### Day 2: rear drivetrain module

**Time Spent:** \~5 hrs
fusion 360 was on fire today. built most of the back end.

* put 2 A2212 motors mirrored and modeled a GT2 pulley system that feeds torque into a single 5mm axle.
* made hex wheel hubs that press-fit onto that same axle — no diff, both wheels spin same speed.
* made a custom bracket that holds both motors tight w/ cutouts and belt tension slots.
* added ribs n’ walls to the pulley block so it doesn’t flex when the car's ripping around.
* everything either snaps in or bolts together. no glue, no epoxy, no drama. full module is swappable like drone arms.

spent too long on belt tension — finally just threw in a top roller and extended the flanges. it’s holding fine now.

---

### Day 3: front steering mess

**Time Spent:** \~4 hrs
ugh steering. didn’t wanna do this but had to.

* made some chunky knuckles w/ pivot arms and mini stub axles for the front wheels.
* linked up the MG996R servo to a drag link + tie rod. it’s janky but it works.
* kinda followed ackermann steering stuff? not too serious. close enough for dirt.
* servo sits in a nice little pocket above the axle — hidden and outta the way.
* front axle bolts to the spine w/ 4 screws. fast to swap if anything breaks.

also made the front wheels easy to remove — just pull a pin, no micro hex screws in the sand anymore.

---

### Day 4: chassis spine

**Time Spent:** \~5 hrs
made the skeleton. simple, strong, modular.

* the chassis is just a long rail. every part bolts on like train cars.
* added slots for everything: front axle, rear pod pivot, ESCs, battery tray, RX.
* made zip tie guides and wire tunnels in the side walls — zero spaghetti cables.
* tried to keep everything symmetrical so future changes don’t break stuff.
* split the whole spine into 3 printable sections (<200mm). added pegs so it snaps together clean.

every part’s mounted using M3 nuts and screws. they’re everywhere. everything locks down tight now.

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

---

### Day 6: full assembly test

**Time Spent:** \~4 hrs
put everything together in cad. moment of truth.

* imported all the modules into one file — front, mid, back.
* made sure GT2 belt clears the chassis and wires don’t rub anything.
* servo angle, steering travel — checked everything. no weird clashes.
* tweaked hole sizes and added chamfers so M3 screws go in easy.
* modeled some tires w/ chunky treads just to get the vibe. looks sick.

this thing fits together like LEGO. every part either slots or bolts. super satisfying.

---

### Day 7: print prep

**Time Spent:** \~4 hrs
prep day. time to get slicer-ready.

* fixed orientation for every STL so there’s less support and stronger prints.
* named files properly — no more "final\_final\_real.stl" stuff.
* double-checked tolerances using the caliper tool in cad. everything should fit.
* added pegs + markers to help line things up while assembling.
* estimated around 380g PLA total, 11-12 hrs of print time unless the bed acts up.

also made a proper BOM with names, weights, print time, part count, and how stuff fits. everything’s organized.

---

### status update

all cad files are final and exported. STLs are cleaned up and sitting in the print folder. now just waiting for the real-world parts to show up:

* 2x A2212 1000KV motors
* GT2 5mm pulley kit + 200mm belt
* 2x 30A ESCs + RX and TX

as soon as stuff lands, printing begins. fingers crossed it drives like a beast and doesn’t melt the first time i hit throttle.

---


