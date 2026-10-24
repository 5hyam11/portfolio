# Shyam Narayan Sundararajan — Portfolio

Personal portfolio for Shyam Narayan Sundararajan, Robotics Engineering student at UC Santa Cruz and Software Integration Intern at NVIDIA.

🔗 **Live site:** [5hyam11.github.io/portfolio](https://5hyam11.github.io/portfolio)

---

## Design

An editorial, paper-and-ink layout with a signal-orange accent and a "night shift" dark mode.

- **Live A\* hero.** The background is an occupancy grid running a real A\* search (8-connected, octile heuristic, no corner cutting). A robot chases your cursor and re-plans every step, and a readout shows path cost, expanded nodes, and solve time. Click to toggle obstacles; on touch devices, tap to send the robot somewhere.
- **Project index.** A numbered, filterable list (Perception, Embedded, Manipulation, Planning, AI, Research). Each row expands into highlights, metrics, stack, and a repo link.
- **Spec sheet** for skills, a timeline for experience, and an inverted contact block.
- Respects `prefers-reduced-motion` and `prefers-color-scheme`, and remembers the theme you pick.

## Projects Featured

| Project | Repo |
|---|---|
| ShopShadow: autonomous shopping cart (CruzHacks) | — |
| ACT-Tac-Toe: VLA robotic manipulation | — |
| Gyro: autonomous competition robot (winner) | [Gyro_Robot](https://github.com/5hyam11/Gyro_Robot) |
| QUBO Path Planner: quantum-inspired planning research | [Qubo_path_planner](https://github.com/5hyam11/Qubo_path_planner) |
| DreamLoop: generative-weather AV perception stress test | [NemoClaw](https://github.com/5hyam11/NemoClaw) |
| Eco-Drive CV: real-time perception on a Raspberry Pi | [Pi_Cv_implementation](https://github.com/5hyam11/Pi_Cv_implementation) |
| Car Perception Net: multi-task car perception | [Car_perception](https://github.com/5hyam11/Car_perception) |
| Multi-Task Perception: segmentation, depth, and normals | [Multi_Taskl_Perception](https://github.com/5hyam11/Multi_Taskl_Perception) |
| SignBridge: iOS sign language ↔ speech | [Sign_Bridge](https://github.com/5hyam11/Sign_Bridge) |
| Jarvis: document-grounded RAG | [jarvis-rag](https://github.com/5hyam11/jarvis-rag) |
| LLM-Symbolic Reasoning: AIEA Lab | [aiea-lab.github.io](https://github.com/5hyam11/aiea-lab.github.io) |

To add a project, append an object to the `PROJECTS` array in `index.html`. Filters and counts update on their own.

## Stack

Pure HTML/CSS/JS in a single file. No frameworks, no build step. The only external resource is Google Fonts (Space Grotesk, Instrument Serif, JetBrains Mono).

## Running Locally

Open `index.html` in a browser, or serve the folder:

```bash
git clone https://github.com/5hyam11/portfolio.git
cd portfolio
npx http-server .
```

## Deployment

Hosted via GitHub Pages from the `main` branch.
