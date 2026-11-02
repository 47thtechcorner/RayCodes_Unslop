<div align="center">
  <a href="https://youtu.be/njjLK3l6gKc">
    <img src="https://img.youtube.com/vi/njjLK3l6gKc/0.jpg" alt="Unslop + Google Antigravity: This New Design Skill Kills AI Frontend Slop!">
  </a>
  <h3>📺 <a href="https://youtu.be/njjLK3l6gKc">Watch the full video on YouTube</a></h3>
</div>

# Unslop: Frontend Design Architecture

> [!NOTE]
> System-level design optimization skill created by Damir Sokolovsky ([@heydamir](https://x.com/heydamir), licensed under CC BY 4.0). Unslopping turns vibecoded, AI-generated UI into designed interfaces with distinct character—preserving product features and content while making every spacing token, color, word, and visual deliberate.

![License](https://img.shields.io/badge/License-CC--BY--4.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Antigravity%20%2F%20Claude%20Code-purple.svg)
![Skill](https://img.shields.io/badge/Skill-unslop-green.svg)

---

## 🛠️ Antigravity Agent Setup & Skill Installation

Ask your Antigravity agent to inspect the official repository and set up the skill inside your workspace:

### Agent Setup Prompt
```text
Please inspect the official unslop skill repository at https://github.com/heydamir/unslop (specifically the skill definition in https://github.com/heydamir/unslop/tree/main/skills/unslop). Install the skill into my active workspace under `.agents/skills/unslop/` by fetching SKILL.md and its reference guides. Once installed, reload the workspace skills with `/skills reload` and confirm unslop is ready.
```

### Manual Installation (PowerShell)
```powershell
# Clone official unslop repository
git clone https://github.com/heydamir/unslop.git .temp_unslop

# Copy skill definition into Antigravity workspace skills directory
New-Item -ItemType Directory -Force -Path .agents/skills/unslop | Out-Null
Copy-Item -Recurse -Force .temp_unslop/skills/unslop/* .agents/skills/unslop/
Remove-Item -Recurse -Force .temp_unslop

# Reload active workspace skills in Antigravity chat
/skills reload
```

---

## 🔄 Input-to-Output Transformation Showcase

Every demo case in this repository pairs a raw AI-generated input with an unslop-refined output:

| Case | Raw Slop Input | Unslop Refined Output | Core Craft Applied |
| :--- | :--- | :--- | :--- |
| **Case A** | `input_a_dashboard_slop.html` | `output_a_dashboard_refined.html` | Snaps arbitrary 13px padding to a strict 4px/8px scale, drains purple hue glows into quiet graphite chrome, and isolates color into one mint telemetry moment. |
| **Case B** | `input_b_navigation_slop.html` | `output_b_navigation_refined.html` | Replaces random emoji menu prefixes with 16px/1.5-stroke vector line icons, establishes dense 34px navigation rows, and normalizes shouty uppercase text to sentence case. |
| **Case C** | `input_c_hero_landing_slop.html` | `output_c_hero_landing_refined.html` | Strips out floating 3D orb placeholders and generic hype copy, introducing an asymmetric split with calm headline space and a real code product window. |

---

## ⚡ 1-Liner Agent Prompts

Run these concise 1-liner prompts in your Antigravity chat targeting each input:

### 1. Dashboard Redline Pass (Input A → Output A)
```text
Run @unslop on Input A: establish the 5-line direction, quiet the chrome into graphite neutrals, snap all spacing to a 4px/8px grid, and focus color into one telemetry chart moment.
```

### 2. Quiet Navigation & Icon Normalization (Input B → Output B)
```text
Run @unslop on Input B: drop all emoji decorations into unified 16px line icons, normalize tracked uppercase labels to sentence case, and establish quiet 34px navigation rows with 2px gaps.
```

### 3. Real Product Hero & Clear Copy (Input C → Output C)
```text
Run @unslop on Input C: strip out decorative floating blobs, write clear grounded copy without hype words, and build a real code-based product preview in an asymmetric split layout.
```

---

## 🎯 What Good Looks Like

- **One bright element**: Each screen has one polished moment carrying color and craft (a rendered object, painted scene, or rich chart). Everything around it stays quiet.
- **Quiet chrome**: Navigation, buttons, and borders use tinted neutrals and at most one accent. Nothing glows or competes.
- **A clear idea**: One sentence explains what the visual shows and why it belongs to this product.
- **Text on calm space**: Headlines sit on empty layout space with one primary action and at most one secondary link.
- **Real product, real material**: Previews look like the actual application with plausible data, weight, light, and shadow.

---

<sub><b>Keywords:</b> Unslop github, Unslop CLI, frontend slop, vibecoding fix, AI frontend, UI audit, CLI design, Claude skill, AI design, UI transformation, automated UI, UI unslop, frontend killer, vibecoded AI, frontend agent, unslop skill, claude code, heydamir unslop, antigravity skills, claude skills, ui ux pro max, apple design skill, anti slop skill, claude design skill, claude ui design, taste skill claude, impeccable claude, motion design skill, unslop ui, damir sokolovsky, claude code design, frontend design claude, claude web design, antigravity cli, google antigravity, claude frontend design, taste design skill, awesome design skill, unslop ai, heydamir unslop github, damir sokolovsky github</sub>
