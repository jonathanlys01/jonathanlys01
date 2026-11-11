<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/dark.jpeg">
  <source media="(prefers-color-scheme: light)" srcset="assets/light.jpeg">
  <img alt="Jonathan Lys" src="assets/dark.jpeg" width="100%">
</picture>

# Jonathan Lys
<h1 align="center">Jonathan Lys</h1>

> I study how masked models learn representations and generate diverse outputs.
<p align="center">
  <b>PhD Candidate in Machine Learning · IMT Atlantique (<a href="http://recherche.imt-atlantique.fr/brain/">BRAIN Team</a>)</b><br>
  <i>Investigating discrete diffusion, diversity-aware decoding, and foundation models for biosignals.</i>
</p>

Third-year PhD candidate at **[IMT Atlantique](https://www.imt-atlantique.fr/en)** in the **[BRAIN team](http://recherche.imt-atlantique.fr/brain/)** (Brest, France). My work focuses on discrete diffusion, diversity-aware decoding, and EEG foundation models.
<p align="center">
  <a href="https://jonathanlys01.github.io"><img src="https://img.shields.io/badge/Website-jonathanlys01.github.io-2563EB?style=flat-square&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://scholar.google.com/citations?user=heUq7WEAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-Citations-4285F4?style=flat-square&logo=google-scholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://huggingface.co/jonathan-lys"><img src="https://img.shields.io/badge/Hugging_Face-jonathan--lys-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="https://orcid.org/0009-0006-7908-843X"><img src="https://img.shields.io/badge/ORCID-0009--0006--7908--843X-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://www.linkedin.com/in/jonathan-lys/"><img src="https://img.shields.io/badge/LinkedIn-jonathan--lys-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:jonathan.lys@imt-atlantique.org"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Previously Visiting Scientist at **Sony Europe** and Research Intern at **Criteo AI Lab**.
---

[Website](https://jonathanlys01.github.io) &nbsp;·&nbsp;
[Google Scholar](https://scholar.google.com/citations?user=heUq7WEAAAAJ) &nbsp;·&nbsp;
[Hugging Face](https://huggingface.co/jonathan-lys) &nbsp;·&nbsp;
[ORCID](https://orcid.org/0009-0006-7908-843X) &nbsp;·&nbsp;
[LinkedIn](https://www.linkedin.com/in/jonathan-lys/) &nbsp;·&nbsp;
[Email](mailto:jonathan.lys@imt-atlantique.org)
### 🔬 Research Map

```mermaid
flowchart LR
    A[<b>Representation & Generation</b>] --> B[<b>Foundation Models</b><br>EEG & Biosignals]
    A --> C[<b>Generative Dynamics</b><br>Discrete Diffusion]
    A --> D[<b>Model Mechanics</b><br>Inference & Efficiency]

    B --> B1["<b>REVE</b> <i>(NeurIPS 2025)</i><br>25k subjects · Braindecode"]
    C --> C1["<b>D5P4</b><br>Partition DPP Diversity"]
    D --> D1["<b>Inner Loop Inference</b><br>Latent layer computation"]
    D --> D2["<b>TensLoRA</b> <i>(ICASSP 2026)</i><br>Tensor low-rank adaptation"]
```

---

### Selected Work
### 🌟 Selected Work & Contributions

* **REVE: A Foundation Model for EEG — Adapting to Any Setup with Large-Scale Pretraining on 25,000 Subjects**  
  *NeurIPS 2025*  
  Pretrained foundation model adapting to arbitrary electrode layouts across clinical and cognitive domains.  
  [[Paper]](https://arxiv.org/abs/2510.21585) &nbsp;·&nbsp; [[Project Page]](https://brain-bzh.github.io/reve/) &nbsp;·&nbsp; [[Models & Data]](https://huggingface.co/collections/brain-bzh/reve) &nbsp;·&nbsp; [[Braindecode]](https://braindecode.org/stable/generated/braindecode.models.REVE.html) &nbsp;·&nbsp; [[Embedding Atlas]](https://jonathanlys01.github.io/projects/reve-atlas/)
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://brain-bzh.github.io/reve/">REVE</a></h3>
      <p><b>NeurIPS 2025</b> · <i>A Foundation Model for EEG</i></p>
      <p>Adapting to any recording setup with large-scale pretraining across 25,000 subjects and clinical/cognitive tasks.</p>
      <p>
        <a href="https://arxiv.org/abs/2510.21585"><img src="https://img.shields.io/badge/Paper-arXiv%3A2510.21585-B31B1B?style=flat-square" alt="Paper"></a>
        <a href="https://huggingface.co/collections/brain-bzh/reve"><img src="https://img.shields.io/badge/HuggingFace-Collection-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HF Collection"></a>
        <a href="https://braindecode.org/stable/generated/braindecode.models.REVE.html"><img src="https://img.shields.io/badge/Docs-Braindecode-0284C7?style=flat-square" alt="Braindecode"></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎲 <a href="https://arxiv.org/abs/2603.19146">D5P4</a></h3>
      <p><b>Preprint 2026</b> · <i>Discrete Diffusion Decoding</i></p>
      <p>Partition Determinantal Point Process (DPP) to balance quality and diversity in parallel discrete diffusion generation.</p>
      <p>
        <a href="https://arxiv.org/abs/2603.19146"><img src="https://img.shields.io/badge/Paper-arXiv%3A2603.19146-B31B1B?style=flat-square" alt="Paper"></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔄 <a href="https://arxiv.org/abs/2602.14759">Inner Loop Inference</a></h3>
      <p><b>EUSIPCO 2026</b> · <i>Transformer Capabilities</i></p>
      <p>Extending computation depth in frozen Transformers by revisiting internal layers during inference without retraining.</p>
      <p>
        <a href="https://arxiv.org/abs/2602.14759"><img src="https://img.shields.io/badge/Paper-arXiv%3A2602.14759-B31B1B?style=flat-square" alt="Paper"></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://arxiv.org/abs/2509.19391">TensLoRA</a></h3>
      <p><b>ICASSP 2026</b> · <i>Efficient Adaptation</i></p>
      <p>Tensor alternatives for low-rank adaptation, unlocking flexible parameter-efficient fine-tuning.</p>
      <p>
        <a href="https://arxiv.org/abs/2509.19391"><img src="https://img.shields.io/badge/Paper-arXiv%3A2509.19391-B31B1B?style=flat-square" alt="Paper"></a>
      </p>
    </td>
  </tr>
</table>

* **D5P4: Partition Determinantal Point Process for Diversity in Parallel Discrete Diffusion Decoding**  
  *arXiv 2026*  
  Balancing quality and generation diversity in parallel discrete diffusion models.  
  [[Paper]](https://arxiv.org/abs/2603.19146)
---

* **Inner Loop Inference for Pretrained Transformers: Unlocking Latent Capabilities Without Training**  
  *EUSIPCO 2026*  
  Extending computation depth in frozen Transformers by revisiting internal layers during inference.  
  [[Paper]](https://arxiv.org/abs/2602.14759)
### 🛠️ Toolkit & Technologies

* **TensLoRA: Tensor Alternatives for Low-Rank Adaptation**  
  *ICASSP 2026*  
  Tensor decompositions for parameter-efficient adaptation of large models.  
  [[Paper]](https://arxiv.org/abs/2509.19391)
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/Braindecode-0284C7?style=flat-square" alt="Braindecode">
  <img src="https://img.shields.io/badge/MNE--Python-3776AB?style=flat-square" alt="MNE">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/CUDA_/_SLURM-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA / SLURM">
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX">
</p>

---

### Background
### 🎓 Background & Experience

* **2024 – Present** — PhD Candidate in Machine Learning, IMT Atlantique *(BRAIN team)*
* **2024** — Visiting Scientist, Sony Europe *(Brest, France)*
* **2023 – 2024** — M.Sc. in Signal, Vision, Waves, Systems (SiVOS), Université de Rennes 1
* **2023** — Research Intern, Criteo AI Lab *(Paris, France)*
* **2023** — Academic Exchange, University of Technology Sydney (UTS)
* **2021 – 2024** — Diplôme d'Ingénieur (M.Sc. in Engineering), IMT Atlantique
* **2024 – Present** — **PhD Candidate in Machine Learning**, IMT Atlantique *(BRAIN Team, Brest)*
* **2024** — **Visiting Scientist**, Sony Europe *(Brest, France)*
* **2023 – 2024** — **M.Sc. SiVOS** *(Signal, Vision, Waves, Systems)*, Université de Rennes 1
* **2023** — **Research Intern**, Criteo AI Lab *(Paris, France)*
* **2023** — **Academic Exchange**, University of Technology Sydney (UTS)
* **2021 – 2024** — **Diplôme d'Ingénieur**, IMT Atlantique
