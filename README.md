<picture>
  <source media="(max-width: 600px)" srcset="assets/hero-phone.webp">
  <img src="assets/hero.webp" width="100%" alt="A sunny meadow moving in the wind. Srinath H: I build the whole product and the small models inside it.">
</picture>

<p align="center">
  <a href="https://openatc.aeon-labs.site"><img src="assets/pill-atc.webp" height="42" alt="OpenATC"></a>&nbsp;
  <a href="https://stratify.aeon-labs.site"><img src="assets/pill-st.webp" height="42" alt="Stratify MCP"></a>&nbsp;
  <a href="https://huggingface.co/srinath-exe"><img src="assets/pill-hf.webp" height="42" alt="Hugging Face"></a>&nbsp;
  <a href="https://www.linkedin.com/in/srinath-exe"><img src="assets/pill-li.webp" height="42" alt="LinkedIn"></a>
</p>

I take a product from the first sketch to production, and when it needs a model small enough to run in a browser tab, I train that too. These two are mine, live, and MIT licensed.

<a href="https://openatc.aeon-labs.site">
<picture>
  <source media="(max-width: 600px)" srcset="assets/openatc-phone.webp">
  <img src="assets/openatc.webp" width="100%" alt="OpenATC: the game's night film of a landing, taxi, pushback and take-off at San Francisco, with the spoken calls typed over it.">
</picture>
</a>

Key the mic and talk to the traffic. A speech model I fine-tuned hears you, a 2M model I trained from scratch works out the command, and the pilot reads it back and flies it. No large language model and no GPU at run time.

**[Play](https://openatc.aeon-labs.site)** · **[Code](https://github.com/Srinath-exe/OpenSkyATC)** · **[Speech model](https://huggingface.co/srinath-exe/skycontrol-atc-asr-110m)** · **[Command model](https://huggingface.co/srinath-exe/skycontrol-atc-command-2m)**

<a href="https://stratify.aeon-labs.site">
<picture>
  <source media="(max-width: 600px)" srcset="assets/stratify-phone.webp">
  <img src="assets/stratify.webp" width="100%" alt="Stratify MCP: a question typed into ChatGPT, the backtest running day by day, and the result after charges.">
</picture>
</a>

Describe an options strategy in plain words and get it backtested on real one-minute NIFTY and SENSEX prices, after every charge. Then it tells you how far to trust the result.

**[Try it](https://stratify.aeon-labs.site)** · **[Code](https://github.com/Srinath-exe/stratify-mcp)** · **[npm](https://www.npmjs.com/package/stratify-mcp)** · **[PyPI](https://pypi.org/project/stratify-mcp/)** · **[MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=site.aeon-labs/stratify)**

### Measured

<picture>
  <source media="(max-width: 600px)" srcset="assets/numbers-phone.webp">
  <img src="assets/numbers.webp" width="100%" alt="2M weights in System One, trained from scratch, 2 MB, runs in the browser. 150 ms for ATC-ASR to hear a five-second call on a CPU. 372M one-minute option bars behind Stratify MCP's answers. 0.21 s engine time for a one-year weekly backtest, median.">
</picture>

<sub>150 ms: median of 320 clips, 2 CPU threads. 0.21 s: one request at a time on the 8-core server, August 2026.</sub>

### Built with

<picture>
  <source media="(max-width: 600px)" srcset="assets/stack-phone.svg">
  <img src="assets/stack.svg" width="100%" alt="PyTorch, ONNX Runtime, Hugging Face, WebAssembly, Python, FastAPI, MCP, LangGraph, LiveKit, TypeScript, Next.js, React, three.js, Flutter, ClickHouse, PostgreSQL, Redis, Docker, GitHub Actions">
</picture>
