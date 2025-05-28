# REPRO-Bench

**📄 Official codebase for the ACL 2025 paper: _REPRO-Bench: Can Agentic AI Systems Assess the Reproducibility of Social Science Papers?_**


## 📦 Dataset

The REPRO-Bench dataset is hosted on Hugging Face:

```bash
git clone https://huggingface.co/datasets/chuxuan/REPRO-Bench
cd REPRO-Bench
git lfs pull
````

It includes:

* 112 task instances (PDFs + code + data)
* Gold-standard reproducibility annotations
* Public reproduction reports

---

## 🚀 Getting Started

### Run SWE-Agent

```bash
bash SWE-Agent/run_all.sh
```

### Run AutoGPT

```bash
bash AutoGPT/classic/original_autogpt/run_all.sh
```

### Run CORE-Agent

```bash
bash CORE-Agent/classic/original_autogpt/run_all.sh
```