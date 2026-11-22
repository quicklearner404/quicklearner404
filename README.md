## Fatima Kashif

I'm a final-year Computer Science student at FAST-NUCES (graduating 2026), focused on NLP, LLM agents and retrieval-augmented generation.

Most of my work sits between building models and checking that they actually work: fine-tuning and serving transformer models, writing evaluations that hold up to scrutiny, and making results reproducible in CI. I'm looking for roles in applied ML and NLP engineering.

### Selected projects

**[ClinicalNER](https://github.com/quicklearner404/ClinicalNER)**
Extracts drugs and diseases from clinical text on ordinary CPUs. I fine-tuned DistilRoBERTa on BC5CDR (F1 0.857) and exported it to INT8 ONNX, making it 3.8× faster per sentence and 4× smaller with no loss in accuracy. It's served with FastAPI and Docker, and CI tests the published model end to end.

**[ResuMate](https://github.com/quicklearner404/ResuMate-nlp)** · [live demo](https://resumate-nlp-xog54tmzkmdswhloiun2bn.streamlit.app/)
A resume parser and job matcher combining a DistilBERT NER model with rule-based extraction. While cleaning up this team project, I found that its original evaluation reported 100% precision by construction. I rebuilt the scoring and fixed two post-processing bugs it uncovered, raising exact-match F1 from 58.8% to 67.1%. CI recomputes the results on every change.

**[Research Compass AI](https://github.com/quicklearner404/research-compassAI)**
A research assistant built on a tool-calling agent that searches arXiv, GitHub and the web. It checks that every cited link came from a tool result, and includes an offline benchmark that shows where its query routing fails. Built with FastAPI and React, with 67 tests.

### Tools

Python, PyTorch, Hugging Face Transformers, ONNX Runtime, spaCy, scikit-learn, FastAPI, Streamlit, Docker, GitHub Actions, SQL, Java, TypeScript

### Links

[Hugging Face](https://huggingface.co/quicklearner404)
