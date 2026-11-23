# Ridwan Oluwaseun Bello

**Ph.D. Candidate in Computer Science** | The University of Alabama (Expected Dec 2027 / May 2028)  
Researching **Automatic Speech Recognition (ASR)**, **Intra-Sentential Code-Switching**, **Parameter-Efficient Fine-Tuning (PEFT)**, and **Low-Resource/Accented Speech Foundation Models**.

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=nz3_o-IAAAAJ&hl=en)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-ridwanbello-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/ridwanbello)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ridwan_Bello-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ridwan-o-bello)
[![Email](https://img.shields.io/badge/Email-robello2%40crimson.ua.edu-990000?style=flat&logo=gmail&logoColor=white)](mailto:robello2@crimson.ua.edu)

---

### Research Focus & Highlights
* **Intra-Sentential Code-Switched ASR (YECS):** Investigating acoustic-linguistic failure modes at language switch boundaries in Yoruba-English speech across Whisper, SeamlessM4T, FastConformer, and OmniASR using switch-point evaluation metrics (**PIER** and **SPER**).
* **Parameter-Efficient Adaptation for Accented ASR (AfriSpeech-200):** Benchmarking LoRA, DoRA, and AdaLoRA on Whisper and wav2vec 2.0/WavLM—achieving an **82% relative WER reduction** over zero-shot Whisper while preserving general-domain performance (**4.5% vs. 5.7% WER** on LibriSpeech `test-clean`).
* **Production ML & Full-Stack Engineering:** 4+ years of prior software engineering experience building high-concurrency Python/FastAPI microservices and full-stack web systems.

---

### Featured Repositories

| Repository | Domain | Key Focus & Stack |
| :--- | :--- | :--- |
| **[`yecs-codeswitch-asr`](https://github.com/ridwanbello/yecs-codeswitch-asr)** | Code-Switched ASR | Modular benchmarking & switch-aware PEFT pipeline for Yoruba-English speech (`Whisper`, `SeamlessM4T`, `FastConformer`, `OmniASR`) |
| **[`afrispeech-peft-asr`](https://github.com/ridwanbello/afrispeech-peft-asr)** | Accented Speech & PEFT | LoRA/DoRA fine-tuning & out-of-domain retention evaluation on AfriSpeech-200 and LibriSpeech (`PyTorch`, `PEFT`, `Transformers`) |
| **[`switch-point-asr-metrics`](https://github.com/ridwanbello/switch-point-asr-metrics)** | Speech Evaluation | Lightweight Python toolkit for computing **PIER**, **SPER**, and boundary-level error diagnostics on code-switched transcripts |
| **[`ml-fraud-detection`](https://github.com/ridwanbello/ml-fraud-detection)** | Production NLP API | Real-time SMS/URL/phone fraud screening service built with `FastAPI`, `Python`, and `scikit-learn` |

---

### Technical Stack
* **Speech & Audio:** Whisper, SeamlessM4T, FastConformer, OmniASR, wav2vec 2.0, WavLM, `torchaudio`, `librosa`, `jiwer`
* **ML & Training:** Python, PyTorch, Hugging Face (`transformers`, `peft`, `datasets`, `evaluate`), `bitsandbytes`, LoRA/DoRA
* **Engineering & Infra:** FastAPI, Docker, Git, Linux, SQL, React, TypeScript, LaTeX
