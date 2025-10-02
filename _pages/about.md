---
permalink: /
title: "Welcome to my personal website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<h2 style="font-family:Times New Roman, serif; font-weight:600; border-bottom:none; padding-bottom:4px;">
BIO
</h2>

I am currently a fourth-year undergraduate student in the Department of Electronic Engineering at Tsinghua University. I began my research journey at [NICSEFC](https://nicsefc.ee.tsinghua.edu.cn/) under the supervision of Prof. [Yu Wang](https://web.ee.tsinghua.edu.cn/wangyu) and Dr. [Zhenhua Zhu](https://nicsefc.ee.tsinghua.edu.cn/people/ZhenhuaZhu). At present, I am also a research intern at the [Parallel Data Lab](https://www.pdl.cmu.edu/index.shtml), Carnegie Mellon University, working with Prof. [Phillip Gibbons](https://www.cs.cmu.edu/~gibbons/) and collaborating closely with Prof. [Guy Blelloch](https://www.cs.cmu.edu/~guyb/). 


---

<h2 style="font-family:Times New Roman, serif; font-weight:600; border-bottom:none; padding-bottom:4px;">
Research Interests
</h2>

- Computer Architecture & Computer System
- Parallel & Distributed Computing  
- Algorithms & System Engineering  
- Heterogeneous-Memory Systems & Processing-in-Memory  
- Cloud Computing  

---

<style>
/* Section Title: elegant, academic */
.section-title {
  font-family: Georgia, serif;
  font-weight: 700;
  letter-spacing: 0.5px;
  margin: 28px 0 12px;
}

/* Publications container */
.pubs-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 16px;
}

/* Card: left fixed thumbnail, right content */
.pub-card {
  display: grid;
  grid-template-columns: 120px 1fr; /* left thumb 120px, right auto */
  gap: 16px;
  align-items: start;
  padding: 14px;
  border: 1px solid #eee;
  border-radius: 14px;
  background: #fff;
  box-shadow: 0 1px 3px rgba(0,0,0,.04);
}

/* Thumbnail: small, centered crop */
.pub-thumb {
  width: 100%;
  height: 90px;
  object-fit: cover;
  object-position: center;
  border-radius: 10px;
  background: #f6f7f9;
  display: block;
}

/* Right content */
.pub-venue {
  display: inline-block;
  font-size: 12px;
  font-weight: 700;
  padding: 2px 10px;
  border-radius: 999px;
  background: #eef2ff; /* default blue-ish badge */
  color: #2b3a90;
  margin: 0 0 8px;
}
.pub-title {
  margin: 0 0 6px;
  font-weight: 650;
  line-height: 1.25;
}
.pub-meta {
  margin: 6px 0 12px;
  color: #555;
  font-size: 0.95em;
}

/* Action buttons */
.pub-actions a {
  display: inline-block;
  font-size: 13px;
  font-weight: 600;
  padding: 6px 10px;
  margin: 0 8px 0 0;
  border-radius: 8px;
  text-decoration: none;
  border: 1px solid #ddd;
}
.pub-actions a:hover { background: #fafafa; }
.pub-actions a.pdf { border-color: #cbd5ff; }   /* blue tone for PDF */
.pub-actions a.code { border-color: #c7f0d8; }  /* green tone for Code */
.pub-actions a.bib { border-color: #ffd7b8; }   /* orange tone for Bib */

/* Responsive: stack on narrow screens */
@media (max-width: 640px) {
  .pub-card { grid-template-columns: 1fr; }
  .pub-thumb { height: 160px; }
}
</style>

<!-- ===== Publications HTML (paste where you want it to appear) ===== -->
<h2 class="section-title">Publications</h2>

<div class="pubs-grid">

  <!-- DAC 2025 -->
  <article class="pub-card">
    <img
      class="pub-thumb"
      src="/assets/papers/DAC2025.png"
      alt="HPIM-NoC thumbnail"
      loading="lazy"
      decoding="async"
    >
    <div>
      <div class="pub-venue">DAC 2025</div>
      <h3 class="pub-title">HPIM-NoC: A Priori-Knowledge-Based Optimization Framework for Heterogeneous PIM-Based NoC</h3>
      <div class="pub-meta">
        Shuai Yuan, Angxin Cai, <strong>Qiushi Lin</strong>, et al.
      </div>
      <div class="pub-actions">
        <a class="pdf" href="https://ieeexplore.ieee.org/document/11132638" target="_blank" rel="noopener">PDF</a>
        <a class="code" href="https://github.com/1784175347/HPIM" target="_blank" rel="noopener">Code</a>
        <!-- <a class="bib" href="/assets/papers/hpim-noc.bib" target="_blank" rel="noopener">BibTeX</a> -->
      </div>
    </div>
  </article>

  <!-- ISQED 2025 -->
  <article class="pub-card">
    <img
      class="pub-thumb"
      src="/assets/papers/analog-digital-partition-thumb.png"
      alt="Analog-Digital Partition thumbnail"
      loading="lazy"
      decoding="async"
    >
    <div>
      <div class="pub-venue" style="background:#f0fff6;color:#1c7a4f;">ISQED 2025</div>
      <h3 class="pub-title">Deep Neural Network Inference Partitioning in Embedded Analog-Digital Hybrid Systems</h3>
      <div class="pub-meta">
        Fabian Kreß, Julian Hoefer, <strong>Qiushi Lin</strong>, et al.
      </div>
      <div class="pub-actions">
        <a class="pdf" href="https://ieeexplore.ieee.org/abstract/document/11014471" target="_blank" rel="noopener">PDF</a>
        <!-- <a class="code" href="https://github.com/yourname/analog-digital-partition" target="_blank" rel="noopener">Code</a> -->
        <!-- <a class="bib" href="/assets/papers/isqed25-partition.bib" target="_blank" rel="noopener">BibTeX</a> -->
      </div>
    </div>
  </article>

  <!-- ICCAD 2025 -->
  <article class="pub-card">
    <img
      class="pub-thumb"
      src="/assets/papers/pim-error-eval-thumb.png"
      alt="PIM Error Evaluation thumbnail"
      loading="lazy"
      decoding="async"
    >
    <div>
      <div class="pub-venue" style="background:#fff6f0;color:#9a4a07;">ICCAD 2025</div>
      <h3 class="pub-title">How Do Errors Impact NN Accuracy on Non-Ideal Analog PIM? Fast Evaluation via an Error-Injected Robustness Metric</h3>
      <div class="pub-meta">
        Lidong Guo, Zhenhua Zhu, <strong>Qiushi Lin</strong>, et al.
      </div>
      <div class="pub-actions">
        <a class="pdf" href="https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/ad81b36e-96d6-4a96-885e-24c6c0f8a739.pdf" target="_blank" rel="noopener">PDF</a>
        <a class="code" href="https://github.com/gld17/NIPA?tab=readme-ov-file" target="_blank" rel="noopener">Code</a>
        <!-- <a class="bib" href="/assets/papers/iccad25-pim-error.bib" target="_blank" rel="noopener">BibTeX</a> -->
      </div>
    </div>
  </article>

</div>



## 🧪 Research Experience

### Task-data Orchestration in Distributed Memory  
**RA**, supervised by Prof. *Phillip Gibbons*, Carnegie Mellon University  
- Designed skew-aware load balancing orchestration for distributed memory systems  
- Implemented with 3,000+ lines of C++/MPI; theoretical scheduling formulation  
- Co-authored and submitted a research paper  

### Microarchitecture & Scheduling for Processing Near Memory  
**RA**, supervised by Prof. *Phillip Gibbons*, Carnegie Mellon University  
- Conducted survey on PNM  
- Planning microarchitecture & orchestration algorithm design as summer intern project  

### Network Partitioning for Analog PIM-Digital Accelerator  
**RA**, supervised by Prof. *Yu Wang*, Tsinghua University  
- Built architecture for hybrid chiplet systems using analog in-memory computing  
- Developed simulation model, optimization techniques for performance evaluation  

### Digital-Analog Heterogeneous PIM-NoC Simulation  
**RA**, supervised by Prof. *Yu Wang*, Tsinghua University  
- Created a configurable simulation framework for heterogeneous multi-core PIM  
- Wrote 4,000+ lines of Python, designed an optimization algorithm for simulation  

### In-Memory Computing Accelerator for LLMs  
**RA**, supervised by Prof. *Yu Wang*, Tsinghua University  
- Designed in-memory computing compiler for LLMs under hardware constraints  
- Built simulator to measure latency, energy, and accuracy trade-offs  

---

## 📚 Publications

### In Preparation  
- Yiwei Zhao\*, **Qiushi Lin**\*, Hongbo Kang, Charles McGuffey, Phillip Gibbons.  
  *(Under submission, title withheld for anonymity)*

### Full Publications  
- **HPIM-NoC: A Priori-Knowledge-Based Optimization Framework for Heterogeneous PIM-Based NoC**  
  *DAC 2025* — Shuai Yuan, Angxin Cai, **Qiushi Lin**, et al.

- **Deep Neural Network Inference Partitioning in Embedded Analog-Digital Hybrid Systems**  
  *ISQED 2025* — Fabian Kreß, Julian Hoefer, **Qiushi Lin**, et al.
  
- **How Do Errors Impact NN Accuracy on Non-Ideal Analog PIM? Fast Evaluation via an Error-Injected Robustness Metric**
  *ICCAD 2025* — Lidong Guo, Zhenhua Zhu, **Qiushi Lin**, et al.

---

## 🛠 Skills

- **Languages**: C/C++, Java, Python, Shell, MPI  
- **Software Tools**: MATLAB, Git  
- **Hardware Tools**: Verilog, Gem5, MNSIM  
- **ML Frameworks**: TensorFlow, PyTorch, CUDA  
- **Others**: Mathematica, LaTeX, AutoCAD  
- **Languages**: English (TOEFL 105), Chinese (native)

---
<div class="pubs-grid">

  <!-- DAC 2025 -->
  <article class="pub-card">
    <img class="pub-thumb" src="/assets/papers/DAC2025.png" alt="HPIM-NoC thumbnail">
    <div>
      <div class="pub-venue">DAC 2025</div>
      <h3 class="pub-title">HPIM-NoC: A Priori-Knowledge-Based Optimization Framework for Heterogeneous PIM-Based NoC</h3>
      <div class="pub-meta">
        Shuai Yuan, Angxin Cai, <strong>Qiushi Lin</strong>, et al.
      </div>
      <div class="pub-actions">
        <a class="pdf" href="https://ieeexplore.ieee.org/document/11132638" target="_blank" rel="noopener">PDF</a>
        <a class="code" href="https://github.com/1784175347/HPIM" target="_blank" rel="noopener">Code</a>
      </div>
    </div>
  </article>

   <!-- ICCAD 2025 -->
  <article class="pub-card">
    <img class="pub-thumb" src="/assets/papers/pim-error-eval-thumb.png" alt="PIM Error Evaluation thumbnail">
    <div>
      <div class="pub-venue" style="background:#fff6f0;color:#9a4a07;">ICCAD 2025</div>
      <h3 class="pub-title">How Do Errors Impact NN Accuracy on Non-Ideal Analog PIM? Fast Evaluation via an Error-Injected Robustness Metric</h3>
      <div class="pub-meta">
        Lidong Guo, Zhenhua Zhu, <strong>Qiushi Lin</strong>, et al.
      </div>
      <div class="pub-actions">
        <a class="pdf" href="https://nicsefc.ee.tsinghua.edu.cn/%2Fnics_file%2Fpdf%2Fad81b36e-96d6-4a96-885e-24c6c0f8a739.pdf" target="_blank" rel="noopener">PDF</a>
        <a class="code" href="https://github.com/gld17/NIPA?tab=readme-ov-file" target="_blank" rel="noopener">Code</a>
      </div>
    </div>
  </article>

  <!-- ISQED 2025 -->
  <article class="pub-card">
    <img class="pub-thumb" src="/assets/papers/analog-digital-partition-thumb.png" alt="Analog-Digital Partition thumbnail">
    <div>
      <div class="pub-venue" style="background:#f0fff6;color:#1c7a4f;">ISQED 2025</div>
      <h3 class="pub-title">Deep Neural Network Inference Partitioning in Embedded Analog-Digital Hybrid Systems</h3>
      <div class="pub-meta">
        Fabian Kreß, Julian Hoefer, <strong>Qiushi Lin</strong>, et al.
      </div>
      <div class="pub-actions">
        <a class="pdf" href="https://ieeexplore.ieee.org/abstract/document/11014471" target="_blank" rel="noopener">PDF</a>
      </div>
    </div>
  </article>

 

</div>

_This page is hosted via GitHub Pages_  

