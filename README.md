## Hey there — Professor Willy here. 👋

<table width="100%">
  <tr>
    <td align="left">
      <strong>Building voice agents, charts, and whatever else seems fun.</strong>
    </td>
    <td align="right">
      <a href="https://github.com/Hot-Coco">GitHub</a> ·
      <a href="https://crates.io/crates/skadoosh">crates.io</a> ·
      <a href="https://www.npmjs.com/package/beaned-charts">npm</a> ·
      <a href="https://github.com/RappleML">@RappleML</a>
    </td>
  </tr>
</table>

I build local-first AI tools, open-source libraries, and polished frontend experiences.

### Main Projects

- Creator of **[Skadoosh](https://github.com/Hot-Coco/Skadoosh)**, a lightning-fast local voice agent framework in Rust — VAD → Whisper STT → streaming LLM → ONNX TTS, with real barge-in, sub-150ms latency, and `#![forbid(unsafe_code)]`. Published on [crates.io](https://crates.io/crates/skadoosh). Dual-licensed MIT / Apache-2.0.

- Creator of **[beaned-charts](https://github.com/Hot-Coco/beaned-charts)**, a beautiful SVG chart library with Bar, Line, Pie, and Donut charts, advanced color palettes, always-visible tooltips, and React components. Published on [npm](https://www.npmjs.com/package/beaned-charts) (v3.3.2) with 8 GitHub stars.

- Contributor to **[stickee](https://github.com/Hot-Coco/stickee)**, a modern desktop sticky-note application built with Tauri, React, TypeScript, and Supabase — featuring encrypted cloud sync, checklists, emoji reactions, and 60+ font choices.

- Built **[YellowRoute](https://github.com/Hot-Coco/YellowRoute)**, a fully responsive one-page website for Miami Kids Buses, a school bus transportation company serving South Florida.

- Authored **97 merged commits** across all repos in 2026, shipping Skadoosh from scaffold to v0.5.0 in ~48 hours — including 15 cookbook examples, tool calling, multimodal support, echo cancellation, and GPU execution providers.

### Skadoosh Pipeline

```
  Mic 🎤  →  Silero VAD  →  Whisper STT  →  LLM Stream  →  Clause Split  →  Kokoro TTS  →  Speaker 🔊
                                      ↑  barge-in cancels turn (lock-free, ~5ms)  ↑
```

- **Streaming at every stage** — clauses are synthesized the moment they land; you never wait for the full reply.
- **Pluggable engines** — swap any STT, LLM, or TTS backend via traits. Mock engines ship in-crate for headless testing.
- **110+ tests** running fully headless in CI. Every modality combination supported: voice, text, files, and wav selftests.

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/Rust-161B22?style=flat&logo=rust&logoColor=F74C00" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-161B22?style=flat&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-161B22?style=flat&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React-161B22?style=flat&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tauri-161B22?style=flat&logo=tauri&logoColor=FFC131" alt="Tauri" />
  <img src="https://img.shields.io/badge/Node.js-161B22?style=flat&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
  <img src="https://img.shields.io/badge/ONNX-161B22?style=flat&logo=onnx&logoColor=005CED" alt="ONNX" />
  <img src="https://img.shields.io/badge/Whisper-161B22?style=flat&logo=openai&logoColor=FFFFFF" alt="Whisper" />
  <img src="https://img.shields.io/badge/Ollama-161B22?style=flat&logo=ollama&logoColor=FFFFFF" alt="Ollama" />
  <img src="https://img.shields.io/badge/Supabase-161B22?style=flat&logo=supabase&logoColor=3ECF8E" alt="Supabase" />
  <img src="https://img.shields.io/badge/SVG-161B22?style=flat&logo=svg&logoColor=FFB13B" alt="SVG" />
  <img src="https://img.shields.io/badge/CSS-161B22?style=flat&logo=css3&logoColor=1572B6" alt="CSS" />
  <img src="https://img.shields.io/badge/HTML-161B22?style=flat&logo=html5&logoColor=E34F26" alt="HTML" />
  <img src="https://img.shields.io/badge/Linux-161B22?style=flat&logo=linux&logoColor=FCC624" alt="Linux" />
</p>

### Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=Hot-Coco&show_icons=true&theme=vision-friendly-dark&hide_border=true&bg_color=0d1117&title_color=FF6B35&icon_color=4ecdc4&text_color=c9d1d9&ring_color=45b7d1&include_all_commits=true&count_private=true" alt="GitHub Stats" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hot-Coco&layout=compact&theme=vision-friendly-dark&hide_border=true&bg_color=0d1117&title_color=FF6B35&text_color=c9d1d9&hide=html" alt="Top Languages" width="49%" />
</p>

<p align="center">
  <img src="https://count.getloli.com/@:Hot-Coco" alt="Profile views" />
</p>
