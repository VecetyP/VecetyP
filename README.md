# Hey there, I'm Vec

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1500&color=39FF14&center=true&vCenter=true&width=600&lines=a+dude+coding+random+things;monocular+3D,+physics+sims,+cellular+automata;classical+CV+where+every+verdict+has+a+reason;silly+web+apps)](https://git.io/typing-svg)

---

### About Me

First-year Computer Engineering student at Chulalongkorn University, on the technical team at GDGoC Chulalongkorn. I build for hackathons and like projects with a hard technical core that still look cool on screen: inverse rendering, single-image 3D reconstruction, wave solvers, cellular automata, that sort of thing. I also tutor math and physics with Manim.

---

### Featured

| | |
|---|---|
| **[BlockShot](https://github.com/VecetyP/BlockShot)** | Turn any image into a Minecraft build that looks exactly like it from one spot. Monocular 3D (MoGe-3, Depth Anything, VGGT) → point cloud → colour-matched blocks → a WorldEdit schematic that puts the camera at your eyes. Ships with a 3D lab for comparing depth models. |
| **[Dynamic Fluid Caustics](https://github.com/VecetyP/Dynamic-Fluid-Caustics)** · [live demo](https://vecetyp.github.io/Dynamic-Fluid-Caustics/) | Draw a shape, and water focuses light into it. Monge–Ampère inverse solve, DCT Poisson steps, shallow-water sim, WebGPU + WGSL compute, Three.js tank. |
| **[Sightline](https://github.com/VecetyP/Sightline)** | Isometric puzzle game where whatever lines up on screen is walkable. Turn the camera until two far-apart ledges meet and they become one path. 24 levels across six worlds, Three.js + Vite. |
| **[ClearVote](https://github.com/VecetyP/U-Hackathon-Demo-ClearVote)** | Thai ballot verification for U-Hackathon 2026. Offline classical CV (OpenCV, no neural net, no training data), every verdict has a reason, 32/32 on the Election Commission benchmark. |
| **[ClassTwin](https://github.com/VecetyP/ClassTwin-Backend-Demo)** | "Turn a 1:200 into a 200:200." LangGraph tutor and teacher agents over a RAG store, Gemini structured output with an offline fallback, grades computed in code and never by the LLM. |
| **[AshGlyph](https://github.com/VecetyP/AshGlyph)** | Reads Conway's Life as Braille. Still lifes, oscillators and spaceships are tracked across generations and mapped to glyphs, rendered live as an embossed dot mesh in Ursina. Chaos reads as blank. |

<details>
<summary><b>More stuff I've built</b></summary>
<br>

**ML & data**
- [ResNet-18 Handsign](https://github.com/VecetyP/ResNet18-Handsign-Classification): ASL alphabet classifier, 98.48% test accuracy via selective fine-tuning and differential learning rates
- [Digit Inference Engine](https://github.com/VecetyP/Hand-Drawn-Digit-Inference-Engine): MLP vs CNN on MNIST (99.03%), plus a Tkinter canvas that predicts what you draw in real time
- [Heart Disease Pipeline](https://github.com/VecetyP/Heart-Disease-Classification-Pipeline): Logistic Regression vs Random Forest vs Gradient Boosting on 13 clinical features, 86.67% test accuracy, serialized pipeline
- [Titanic Classifier](https://github.com/VecetyP/Titanic-Analysis-Classification): feature engineering and a three-model benchmark with 5-fold CV
- [Background People Remover](https://github.com/VecetyP/background-people-remover): local detect-and-inpaint tool for clearing strangers out of photos (in progress)
- [Latent Space Visualization](https://github.com/VecetyP/Latent-Space-Visualization): notebooks from learning PCA and other latent-space methods

**Tools & web**
- [CP Roadmap](https://github.com/VecetyP/Computer-Engineering-Roadmap): interactive DAG of my whole curriculum with prerequisite chains (Cytoscape.js + dagre)
- [Tech Engineering Pathways](https://github.com/VecetyP/Tech-Engineering-Roadmap): free beginner field guide in one HTML file, 68 roles across 10 departments with a skill trail for each
- [EduGraph](https://github.com/VecetyP/EduGraph-Demo) · [live demo](https://vecetyp.github.io/EduGraph-Demo/): hackathon pitch prototype, zero-dependency dashboard
- [University News Pipeline](https://github.com/VecetyP/university-news-pipeline): Apify scrape, local QR decoding, and a Gemini filter that writes a daily digest into an Obsidian note
- [Video2ASCII](https://github.com/VecetyP/Video2ASCII): turns a short GIF into one animated ASCII SVG you can embed in a README (the one at the bottom of this page)
- [I Want YT](https://github.com/VecetyP/I-Want-YT): FastAPI YouTube video/audio downloader, runs locally
- [I Don't Know What to Eat](https://github.com/VecetyP/I-Don-t-Know-What-To-Eat): restaurant roulette with Google Maps, filters, and a decision wheel

**Visual & toys**
- [Math & Physics Animations](https://github.com/VecetyP/Mathematics-Physics-Animations): Manim scenes for Fourier decomposition, gravity fields, calculus proofs
- [Cellular Automata](https://github.com/VecetyP/Cellular-Automata): CA in the terminal, and an interactive version in Ursina
- [3D Cube](https://github.com/VecetyP/3dCube): small terminal toy with ASCII depth shading

</details>

---

### Tech Stack & Tools

#### AI, Machine Learning & Data Science

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Antigravity](https://img.shields.io/badge/Antigravity-000000?style=for-the-badge&logo=googlegemini&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

CNNs and MLPs from scratch, transfer learning with selective layer unfreezing, scikit-learn pipelines with cross-validation and benchmarking, object detection and inpainting. Lately monocular 3D: depth and point-map models (MoGe, Depth Anything, VGGT) and what to build on their output. I also like the non-neural side: classical CV where every decision has a reason, LangGraph agents with RAG, and structured LLM output that falls back to deterministic logic.

#### Game Development & Systems

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![Roblox Studio](https://img.shields.io/badge/Roblox_Studio-000000?style=for-the-badge&logo=robloxstudio&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Ursina](https://img.shields.io/badge/Ursina-000000?style=for-the-badge)

Algorithms and competitive programming, Roblox Studio, microcontrollers, cellular automata.

#### Web, Backend & Graphics

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![WebGPU](https://img.shields.io/badge/WebGPU-5E5DF0?style=for-the-badge)
![WGSL](https://img.shields.io/badge/WGSL-150458?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Cytoscape.js](https://img.shields.io/badge/Cytoscape.js-F68D42?style=for-the-badge)
![Apify](https://img.shields.io/badge/Apify-FF1493?style=for-the-badge&logo=apify&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

GPU compute and shaders, physics simulation in the browser, 3D viewers in Three.js / React Three Fiber, REST APIs and async backends with Pydantic schemas, graph and data visualization, and scraping with the Apify SDK. Most of my frontend is vanilla: HTML/CSS/JS, and hand-built SVG when I need a graph.

#### Design, Media & Visualization

![Manim](https://img.shields.io/badge/Manim-111111?style=for-the-badge)
![Swaptube](https://img.shields.io/badge/Swaptube-400090?style=for-the-badge)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)
![Paint.NET](https://img.shields.io/badge/Paint.NET-002040?style=for-the-badge)
![Filmora](https://img.shields.io/badge/Wondershare_Filmora-00C5CD?style=for-the-badge)

Programmatic math and physics animations, UI design, graphics editing, and video production.

---

### Outside the Code

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@VecetyP)
[![Roblox](https://img.shields.io/badge/Roblox-000000?style=for-the-badge&logo=roblox&logoColor=white)](https://www.roblox.com/users/974129486/profile)
[![Minecraft](https://img.shields.io/badge/Minecraft-62B47A?style=for-the-badge)](https://namemc.com/profile/VecetyP)
[![Wynncraft](https://img.shields.io/badge/Wynncraft-556B2F?style=for-the-badge)](https://wynncraft.com/stats/player/vecetyp)

I run [VecetyP on YouTube](https://www.youtube.com/@VecetyP) (~48K subs), which these days means one upload a year, on April Fools' Day. In Minecraft I mostly play technical modpacks and Wynncraft, where I main an Assassin with the Acrobat archetype. I also play Beat Saber, do ballroom and latin dancing, and practice taekwondo.

[![ascii](ascii.svg)](https://github.com/VecetyP/Video2ASCII)
