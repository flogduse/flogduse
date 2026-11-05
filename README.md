### Adithya Rajesh

**B.Tech Computer Science (AI) — TKM College of Engineering, Kollam**

I build small, complete AI systems - retrieval pipelines, computer vision, agents -
and write down *why* each design choice was made.

---

#### Featured

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[rag-campus-assistant](https://github.com/flogduse/rag-campus-assistant)** | Answers questions only from your documents, with inline citations. MMR retrieval to kill near-duplicate chunks, hybrid cosine + lexical scoring, SSE streaming, swappable LLM provider (Groq / OpenAI / Ollama). Runs without a key in retrieval-only mode. Eval harness scores the real retrieval path in CI: [case study](https://github.com/flogduse/rag-campus-assistant/blob/main/docs/CASE_STUDY.md). | FastAPI · ChromaDB · MiniLM |
| **[gesture-control](https://github.com/flogduse/gesture-control)** | Control Windows with hand gestures - volume, media, scrolling, slides. MediaPipe hand tracking with a separately tested, framework-independent gesture engine. | Python · MediaPipe · OpenCV |
| **[nexapath](https://github.com/flogduse/nexapath)** | AI career copilot for tier-2/3 India - TF-IDF cosine job matching plus a conversational agent. Built during the IBM SkillsBuild internship. Live: <https://nexapath.vercel.app> | Python · NLP · TF-IDF |
| **[sign-language-translator](https://github.com/flogduse/sign-language-translator)** | Live ASL fingerspelling to text. Translation/scale/roll-invariant landmark features, tree classifier at 97.8% top-1, and a tested state machine that turns flickering frame predictions into whole words. | Python · MediaPipe · scikit-learn |

#### Currently building

- **[sign-language-translator](https://github.com/flogduse/sign-language-translator)** — shipped: live webcam ASL fingerspelling with invariant landmark features, a confidence-stabilised text state machine, and a full per-class eval (`docs/eval/metrics.json`). Next: two-hand mode and pause-based word boundaries.
- **[manglish-lora](https://github.com/flogduse/manglish-lora)** — harness shipped: validated corpus contract, LoRA train/eval scripts, one-click Colab recipe. The GPU fine-tune itself is the remaining run.
- Hosted RAG demo — `scripts/deploy_hf_space.py` is ready; needs my Hugging Face token to go live.

#### Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

Open to remote AI evaluation / model-training work and internships.
