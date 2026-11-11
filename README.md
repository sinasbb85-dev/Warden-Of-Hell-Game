# Warden of Hell — 2D Action Shooter

A 2D browser-based action-shooter built in **Construct 3** exploring mental health themes through state-based combat mechanics. 

Instead of traditional combat, players enter a patient's mind to stabilize uninvited negative emotions (Anxiety and Anger) by matching the correct healing spell to each enemy archetype before time runs out.

---

## Gameplay & Controls
* **Aim & Shoot:** Mouse cursor + Left Click
* **Switch Spells:** `E` and `R` keys
* **Objective:** Identify the incoming emotion archetype and apply the corresponding spell to stabilize the patient. Using the mismatched spell increases instability, requiring careful input control under pressure.

---

## Key Technical & Design Features
* **State-Based Combat Logic:** Event-driven state transitions evaluate player spell selection against enemy archetypes, triggering either healing states or instability penalties.
* **Custom UI/HUD & Onboarding:** Built an interactive start screen, introductory cutscene, and in-game tutorial to establish narrative context and mechanics immediately.
* **Real-Time Tracking & Dynamic Endings:** Implemented live countdown timers, patient stability meters, and performance-based win/loss endings.
* **Iterative UX Refinement:** Refactored combat feedback loops and visual indicators based on playtester and instructor critiques to improve player comprehension.

---

## Project Files & Media
* `WardenOfHell.c3p` — Full Construct 3 project source file (includes layouts, event sheets, variables, and custom assets).
