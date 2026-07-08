<h1 align="center">Hey, I'm Happynood 👋</h1>
<h3 align="center">ML Engineer wiring LLMs to run fast, cheap, and correctly</h3>

<p align="center">
I quantize models until they scream, benchmark until the numbers stop lying, and ship the config that actually works on real hardware.
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=LLM+inference+optimization;Quantization+%2B+tool-calling+reliability;Reproducible+benchmarks%2C+not+vibes;Python+%7C+PyTorch+%7C+CUDA" alt="Typing SVG" />
</p>

---

### ⚡ What I actually do

I live at the intersection of **NLP systems** and **inference performance** — the part where a model that works great in a notebook has to survive production VRAM budgets, latency SLAs, and someone asking "wait, does it still call the right tool after we quantized it?"

- 🔬 Benchmark LLM backends (`llama.cpp`, `vLLM`, `transformers`, `ONNX`) head-to-head on identical hardware
- 🗜️ Measure exactly what quantization costs — in tokens/sec, VRAM, *and* tool-calling reliability
- 📐 Build harnesses that produce numbers people can actually reproduce, not screenshots

---

### 🛠 Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,pytorch,docker,fastapi,git,github,linux,bash&perline=8" alt="tech stack icons" />
</p>

**Core:** Python · PyTorch · Transformers &nbsp;|&nbsp; **Inference:** llama.cpp · vLLM · ONNX Runtime &nbsp;|&nbsp; **Tooling:** Docker · FastAPI · GitHub Actions

---

### 🚀 Featured Projects

The quantization trilogy — same measurement philosophy, three different failure surfaces:

<table>
<tr>
<td width="33%" valign="top">

**[🤖 QuantCall](https://github.com/Happynood/quant-toolcall-bench)**
<br>Does quantization break tool-calling? Reproducible SVR/TSA/AC/FCR benchmark across GGUF, AWQ, and GPTQ.

</td>
<td width="33%" valign="top">

**[🔌 QuantMCP](https://github.com/Happynood/quant-mcp-bench)**
<br>Does quantization survive real, unmodified MCP tool schemas — not curated ones? Cross-benchmark consistency against QuantCall came out negative.

</td>
<td width="33%" valign="top">

**[🧠 QuantThink](https://github.com/Happynood/quant-reasoning-bench)**
<br>Does it break reasoning? Measures accuracy/thinking-length/cost-to-solve across weight + KV-cache quants, then recommends the accuracy-optimal config for your VRAM budget.

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

**[⚙️ LLM Inference Benchmark](https://github.com/Happynood/llm-inference-benchmark)**
<br>Config-driven harness comparing latency, VRAM, and quality across backends — with Pareto-optimal recommendations.

</td>
<td width="50%" valign="top">

**[⚽ Match Tracker](https://github.com/Happynood/cv-match-tracker)**
<br>Offline player tracking and post-match statistics for football, from a single fixed tactical camera.

</td>
</tr>
</table>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Happynood&theme=tokyonight&hide_border=true" alt="Streak Stats" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Happynood/Happynood/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Happynood/Happynood/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/Happynood/Happynood/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

### 📫 Let's talk inference

<p align="center">
  <a href="https://huggingface.co/Happynood"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
</p>

<p align="center"><i>"You quantized your model to fit VRAM. Did you also quietly break its ability to call tools?"</i></p>
