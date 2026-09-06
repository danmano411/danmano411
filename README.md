<h1 align="center">Hey, I'm Dan 👋</h1>

<p align="center">
  <b>CS @ Georgia Tech</b> — Intelligence (AI/ML) &amp; Modeling and Simulation<br>
  I build autonomous systems that learn from real and simulated data.
</p>

<p align="center">
  <a href="https://linkedin.com/in/danmano"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:dmano6@gatech.edu"><img src="https://img.shields.io/badge/dmano6@gatech.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/danmano411?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"></a>
</p>

---

## About

I'm a Computer Science student at Georgia Tech, concentrating in **Intelligence (AI/ML)** and **Modeling & Simulation**. Most of what I build lives at the seam where a learned model meets something physical — a material, a sensor, a car, a filesystem — because that's where the interesting failure modes are. A model with an R² of 0.99 on paper is a hypothesis; a model that survives contact with real hardware is a result.

That shows up in three places right now: a **startup**, **personal projects**, and **on campus**.

- 🔭 **Building** — [Tycho](https://swail.dev), a deterministic verification layer for AI agents, and [Claude Explorer](https://github.com/danmano411/claude-explorer), a desktop app for running many Claude Code sessions at once
- 🏎️ **On campus** — computer vision for driverless cone detection with **HyTech Racing**, and applied research with **Data Science @ GT**
- 🧪 **Into** — physics-informed neural networks, graph neural nets on crystal structures, simulation-to-real transfer, and agent infrastructure
- ⚡ **Opinion** — determinism beats vibes; if a system can't tell you *why* it was right, it wasn't
- 📫 **Always glad to hear from people doing similar work** — reach out any time

---

## 🚀 Check out the most recent thing I built

<table>
<tr>
<td width="150" align="center" valign="middle">
  <a href="https://github.com/danmano411/claude-explorer">
    <img src="https://raw.githubusercontent.com/danmano411/claude-explorer/main/img/icon.png" width="120" alt="Claude Explorer">
  </a>
</td>
<td valign="middle">

### [Claude Explorer](https://github.com/danmano411/claude-explorer)

A Windows file manager built around exactly one thing: **launching [Claude Code](https://claude.com/claude-code) from any folder in one click** — then keeping every session you start somewhere you can actually see it.

It browses your filesystem like File Explorer does, but every folder row has an arrow that opens a Claude session *inside the app, in a tab*. Sessions live in named **spaces** you switch between, and a session blocked on a permission prompt marks its tab, its space and the menu — so nothing stalls unnoticed while you're looking somewhere else. The state is read from Claude Code's own hooks, not guessed from terminal output.

<a href="https://github.com/danmano411/claude-explorer/releases"><img src="https://img.shields.io/github/v/release/danmano411/claude-explorer?style=flat-square&color=D97757&label=release" alt="Release"></a>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
<img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron">
<img src="https://img.shields.io/badge/Apache--2.0-4A4A4A?style=flat-square" alt="Apache-2.0">

**[⬇️ Download](https://github.com/danmano411/claude-explorer/releases) · [📖 Read the docs](https://github.com/danmano411/claude-explorer#readme)**

</td>
</tr>
</table>

<sub>Under the hood: an Electron main/preload/renderer split with a frozen IPC contract, real ConPTY terminals via `node-pty`, an in-process **loopback MCP server** that lets a Claude session drive the app itself (list tabs, open a viewer, spawn a session), bundled ripgrep search, a reversible undo stack for every file operation, and a four-leg CI release build for Windows, macOS and Linux.</sub>

---

## 🧰 Tech

**Languages** — roughly in the order I reach for them

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
  <img src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white" alt="CSS">
</p>

**Machine learning & AI**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/PyTorch_Geometric-3C2179?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch Geometric">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph">
  <img src="https://img.shields.io/badge/YOLO-0B23A9?style=for-the-badge&logo=ultralytics&logoColor=white" alt="YOLO">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude">
</p>

**Web & app**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
</p>

**Tools & infrastructure**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code">
</p>

---

## 🛠️ Selected work

<table>
<tr><th align="left" width="230">Project</th><th align="left">What it is</th><th align="left" width="200">Stack</th></tr>

<tr><td valign="top">

**[Tycho](https://swail.dev)**<br>
<sub>[repo](https://github.com/swail-labs/tycho) · [npm](https://www.npmjs.com/package/@swail-labs/tycho)</sub>

</td><td valign="top">

A **deterministic trust layer for AI agents** — it checks whether an agent's tool calls actually did what the agent claimed. The verdict engine runs offline with no model in the loop, reasoning over git state, filesystem diffs, exit codes and database deltas against a ground-truth manifest per tool abstraction. Free and open source for Claude Code, Cursor, Codex and OpenCode. Took it through a **Y Combinator interview** with Garry Tan and Kulveer Taggar.

</td><td valign="top"><sub>Python · LLM integration · PyPI/npm distribution</sub></td></tr>

<tr><td valign="top">

**[Claude Explorer](https://github.com/danmano411/claude-explorer)**

</td><td valign="top">

Desktop app for supervising many Claude Code sessions at once — spaces, split panes, real session state from Claude's own hooks, a loopback MCP server the agent can drive the app through, and undo for every file operation.

</td><td valign="top"><sub>TypeScript · Electron · React · node-pty · MCP</sub></td></tr>

<tr><td valign="top">

**[Multimodal GNN for semiconductors](https://github.com/danmano411/bandgap-1-gnn)**

</td><td valign="top">

Predicts band gap and formation energy straight from crystal structure across a **17,000+ material** dataset from the Materials Project, filtered to thermodynamically stable 0–5 eV semiconductors. Fused graph-level structure, Bravais lattice class and global descriptors into one representation — **R² 0.81** on band gap, **0.98** on formation energy — then wrote a custom **PyTorch C++ extension** for graph aggregation that made CPU training **~2.5× faster**.

</td><td valign="top"><sub>Python · C++ · PyTorch Geometric · pymatgen</sub></td></tr>

<tr><td valign="top">

**[Physics-informed NN on HTEM DB](https://github.com/danmano411/htem-neural-net-pipline)**

</td><td valign="top">

A year of mentored ML research on NREL's High Throughput Experimental Materials Database. Built a **~9,500 sample × ~1,300 feature** training set from raw records, then trained and benchmarked **20 deep networks** varying depth, dropout and batch norm — **−96.59% MSE** and **+60.44% R²** over a scikit-learn linear baseline. Introducing physics equations as learning constraints turned the best architecture into a tuned PINN at **R² 0.9932**.

</td><td valign="top"><sub>Python · PyTorch · scikit-learn · Jupyter</sub></td></tr>

<tr><td valign="top">

**Autonomous Security Engineer**<br>
<sub>team project</sub>

</td><td valign="top">

An autonomous C/C++ security engineer: an LLM pipeline that finds vulnerabilities, writes candidate fixes and runs regression tests. Reproduced and resolved multiple known **CVEs from `magma`**, pairing LLM hypothesis generation with deterministic fuzzing in a Linux sandbox. I built the zero-config compilation pipeline that turns an arbitrary C/C++ GitHub repo into a fuzzable target, using a Bear-traced build model with an LLM repair loop for the edge cases.

</td><td valign="top"><sub>Python · LangGraph · fuzzing · Docker</sub></td></tr>

<tr><td valign="top">

**[Minecraft AI sidecar](https://github.com/danmano411/minecraft-ai-sidecar)**

</td><td valign="top">

A RAG-powered Python sidecar that answers Minecraft questions from the official wiki. Small, self-contained, and a genuinely good excuse to build a retrieval pipeline end to end.

</td><td valign="top"><sub>Python · FastAPI · ChromaDB · Ollama</sub></td></tr>

</table>

**Also contributed to** — [Pebble](https://github.com/Vision84/Pebble) · [Parky](https://github.com/Plate1/Parky)

---

<p align="center">
  <sub>
    Georgia Institute of Technology · B.S. Computer Science, 2029 · Atlanta, GA<br>
    <a href="https://linkedin.com/in/danmano">LinkedIn</a> ·
    <a href="mailto:dmano6@gatech.edu">dmano6@gatech.edu</a>
  </sub>
</p>
