<h1 align="center">CtrlVDiff: Controllable Video Generation via Unified Multimodal Video Diffusion</h1>


<p align="center">
  <b>
    <a href="https://scholar.google.com/citations?hl=en&user=7H29mf4AAAAJ">Dianbing Xi</a><sup>1,2,*</sup>,
    <a href="https://jiepengwang.github.io/">Jiepeng Wang</a><sup>2,*,‡</sup>,
    <a href="https://akira-l.github.io/">Yuanzhi Liang</a><sup>2</sup>,
    Xi Qiu<sup>2</sup>,
    Jialun Liu<sup>2</sup>,
    <a href="https://haopan.github.io/">Hao Pan</a><sup>3</sup>,
    <a href="http://www.cad.zju.edu.cn/home/huo/">Yuchi Huo</a><sup>1</sup>,
    <a href="http://www.cad.zju.edu.cn/home/rwang/">Rui Wang</a><sup>1,†</sup>,
    <a href="https://brotherhuang.github.io/index.html">Haibin Huang</a><sup>1</sup>,
    <a href="https://scholar.google.com/citations?hl=en&user=PXlNTokAAAAJ">Chi Zhang</a><sup>2</sup>,
    <a href="https://xuelongli-link.com">Xuelong Li</a><sup>2,†</sup>
  </b>
</p>



<p align="center">
  *Equal contribution. &nbsp; †Corresponding author. &nbsp; ‡Project leader.
</p>

<p align="center">
  <sup>1</sup>State Key Laboratory of CAD&CG, Zhejiang University  
  <br>
  <sup>2</sup>Institute of Artificial Intelligence, China Telecom (TeleAI)  
  <br>
  <sup>3</sup>Tsinghua University
</p>




<p align="center">
  <a href="https://arxiv.org/pdf/2511.21129" style="font-size:18px;">📄 Paper</a> &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://tele-ai.github.io/CtrlVDiff/" style="font-size:18px;">🌐 Project Page</a>
</p>


## 📌 Intro

<div align="center">
  <img src="assets/teaser.png" width="100%">
  <p><em>CtrlVDiff unifies forward and inverse video generation within a single model, enabling the extraction of all modalities in a single pass. It provides layer-wise control over appearance and structure, facilitating applications such as material editing and object insertion.</em></p>
</div>




## ✨ Highlights

- **Unified Video Framework**: A single model supports both forward and inverse video generation. It can function as a renderer to synthesize videos, and as a decomposer to extract all multimodal representations in just one forward pass.

- **Layer-wise Control Strategy**: To enable a unified model to flexibly handle arbitrary combinations and numbers of input modalities, we introduce a Hybrid Modality Control Strategy (HMCS), which provides hierarchical control over video generation across geometry, appearance, structure, and semantics.

- **MMVideo Dataset**: To support the scale and diversity required for this task, we construct the MMVideo dataset, which includes both real-world and synthetic scenes. It contains 350k video clips paired with rich multimodal annotations, enabling high-quality video generation and decomposition across diverse domains.


## 📜 Citation

```bibtex
@misc{xdb2025ctrlvdiff,
      title={CtrlVDiff: Controllable Video Generation via Unified Multimodal Video Diffusion}, 
      author={Dianbing Xi and Jiepeng Wang and Yuanzhi Liang and Xi Qiu and Jialun Liu and Hao Pan and Yuchi Huo and Rui Wang and Haibin Huang and Chi Zhang and Xuelong Li},
      year={2025},
      eprint={2511.21129},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2511.21129}, 
}
```