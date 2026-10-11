# Viraj Bagga

Computer Science and Data Science at the University of Pittsburgh, Class of 2029. AFROTC cadet on the U.S. Space Force cyber track.

Most of what I build is AI that runs locally: small models, retrieval over sources I can cite, and code that checks what the model says instead of trusting it.

## Projects

**[Grounded](https://github.com/Viraj-Bagga/grounded)** · offline medical triage on a laptop CPU · built solo for SteelHacks XIII
- Fine-tuned Nemotron 3 Nano 4B with LoRA. On 22 held-out cases frozen before training, correct answers went from 45.5% to 81.8%, and answers citing nothing that resolves went from 9/33 to 0/53
- Quantised to a 2.84 GB GGUF that runs on CPU with no internet
- Retrieval over 35 US government health sources, and six guards in app code that check every answer and show the user every removal

**[Iris](https://github.com/Viraj-Bagga/iris-spaceflight-news)** · spaceflight news bot for AFROTC i5 squadrons · [landing page](https://viraj-bagga.github.io/iris-spaceflight-news/)
- LangGraph pipeline: Spaceflight News API, SQLite dedup, full text through Jina Reader, then gpt-4o-mini grades relevance and writes the summary
- Multi-tenant Discord bot: each article is graded once and fanned out to every server, so model cost stays flat as squadrons install it

**[STIG Authoring Pro](https://github.com/Viraj-Bagga/STIG-Generator)** · desktop app for writing STIG benchmarks
- Form-based rule editor with a live XCCDF 1.1 preview, import and export, and autosave recovery
- Linux and Windows binaries built by GitHub Actions; README screenshots captured from the running app in CI

**[NXT Fuel](https://github.com/Viraj-Bagga/NXT-Fuel)** · aircraft refueling request app · [live demo](https://viraj-bagga.github.io/NXT-Fuel/)
- Aircraft-aware fuel and nozzle selection, 52-airport search, and a queue with a live countdown, in one HTML file

## Experience

- **Air Force Research Laboratory, Rome NY** · Cyber Vulnerability Analyst Intern, Summer 2026. VICEROY MAVEN Distinguished Graduate (top 10% of the cohort). System hardening and security compliance work, and a Cyber Blue Book on security standards for underwater AI-enabled data centers.
- **Space Force i5** · National board member and deputy squadron commander. Iris started as the news feed for my squadron.

## Stack

- **Languages:** Python, Java, JavaScript, SQL
- **AI:** PyTorch, Hugging Face PEFT and TRL, llama.cpp, LangGraph, LangChain, retrieval with sqlite-vec and BM25
- **Apps:** React, Vite, discord.py, CustomTkinter
- **Tooling:** Git, GitHub Actions, Playwright, PyInstaller, Linux

[LinkedIn](https://www.linkedin.com/in/viraj-bagga)
