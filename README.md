# 🧙 LEGO Harry Potter Years 1–4 — Archipelago Integration

An experimental project aiming to integrate **LEGO Harry Potter: Years 1–4** into the **Archipelago multiworld system**.

This project focuses on **reverse engineering the game memory** to track progression, define checks, and enable randomized multiworld gameplay.

---

## 🚧 Project Status

⚠️ Work in progress — everything listed below is **subject to change**.

Most systems are still under research (memory mapping, stability, feasibility).
The final implementation may differ significantly from the ideas presented here.

---

## 🎯 Goal

* Track in-game progression in real time
* Define meaningful **checks** and **items**
* Enable **multiworld synchronization** with Archipelago
* Create a stable connector between the game and Archipelago

---

## 🔍 Planned Checks (Ideas)

The following are potential progression checks currently being explored:

* Character / crest / multi-step actions

  * Either each step as an individual check
  * Or full completion as a single check *(TBD)*
* Crest pieces
* Full Hogwarts crest
* True Wizard
* Student in Peril
* Gold bricks
* Red bricks
* Purchasing:

  * Characters
  * Spells
  * Red bricks *(potentially)*
* Completing missions
* Completing lessons
* Character tokens

---

## 🎁 Planned Items (Ideas)

Potential items that could be randomized and sent between players:

* Missions / Freeplay

  * If multiple missions cannot be active simultaneously, progression may be linear
* Abilities / Spells:

  * Dark Magic
  * House-specific abilities
  * Wingardium Leviosa
  * Reducto
  * And more
* Bonus levels
* Character tokens
* Full Hogwarts crest

  * Possibly split into individual crest pieces before completion
* True Wizard
* Student in Peril
* Gold bricks
* Red bricks

---

## 🧠 Technical Approach

This project relies on:

* Memory analysis using tools like Cheat Engine
* Reverse engineering of game structures
* Identifying progression-related variables
* Reading (and potentially writing) memory values
* Integration with the Archipelago client

---

## 🤝 Contributing

Contributions, ideas, and findings are welcome!

Since this project involves reverse engineering, sharing:

* memory discoveries
* offsets
* behavior observations

is especially valuable.

---

## 📌 Notes

Everything in this README is exploratory.
The final system design will depend heavily on what is technically achievable.
