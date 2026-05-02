# MedSympTra

**Know when to seek medical care.**

MedSympTra is a free, browser-based health guidance tool built for the GNEC Hackathon, aligned with **UN Sustainable Development Goal 3 — Good Health and Well-being**.

---

## The Problem

Across rural India and much of the developing world, millions of people face a daily dilemma: when a family member falls ill, they don't know whether to travel hours to a hospital, visit a local clinic, or simply rest at home. This uncertainty leads to two equally dangerous outcomes — overcrowded emergency rooms flooded with non-urgent cases, and preventable deaths caused by delayed care for serious conditions.

MedSympTra was built to close this gap.

---

## What It Does

MedSympTra walks users through **7 simple questions** about their symptoms and returns one of three clear recommendations:

| Result | Meaning |
|---|---|
| Home Care Appropriate | Rest at home, stay hydrated, monitor symptoms |
| Medical Attention Needed | Visit a clinic or doctor within 12–24 hours |
| Emergency — Act Now | Go to the emergency room or call an ambulance immediately |

Each result includes specific action steps, warning signs to watch for, and relevant helpline numbers.

---

## Features

- **7-question symptom checker** — covers primary symptom, duration, severity, age, pre-existing conditions, symptom trend, and distance to care
- **Smart guidance logic** — urgent flags (chest pain, breathing difficulty) and risk factors (elderly, infants, pregnant, chronic illness) automatically escalate the recommendation
- **Health Resources page** — 12 India emergency helplines including ambulance (102/108), mental health, women's helpline, TB, poison control, blood bank, and organ donation
- **ABHA explainer** — information on India's national digital health identity (Ayushman Bharat Health Account)
- **WHO & SDG 3 section** — context on the global health mission this tool supports
- **100% private** — no data is stored, no login required, no tracking

---

## SDG 3 Alignment

MedSympTra directly supports the following SDG 3 targets:

- **3.8** — Achieve universal health coverage, including access to quality essential health services
- **3.d** — Strengthen the capacity of all countries for early warning and risk reduction of national and global health risks

By helping people make informed decisions about when to seek care, MedSympTra reduces strain on overburdened health systems while ensuring serious cases receive timely attention.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Fonts | DM Sans, DM Serif Display (Google Fonts) |
| Backend | None — fully client-side |
| Dependencies | Zero external libraries |

---

## How to Run

MedSympTra is a single HTML file with no build step required.

**Open directly:**
```
Open index.html in any modern browser
```

---

## Project Structure

```
medsymptra/
├── index.html     
└── README.md        
```

---

## Screenshots

| Home Screen | Symptom Checker | Result Screen |
|---|---|---|
| Clean landing page with how-it-works and stats | 7-step guided question flow with progress bar | Color-coded result with action steps and warning signs |

---

## Disclaimer

MedSympTra provides **guidance only** — it is not a medical diagnosis tool and does not replace the advice of a qualified healthcare professional. In a life-threatening emergency, always call 102 or 108 immediately.

---

## Built For

**GNEC Hackathon** — 4th Edition
Theme: UN SDG 3 — Good Health and Well-being
Organized by: Global NGO Executive Committee (GNEC)

---

*MedSympTra — Free. Private. Built for communities that need it most.*