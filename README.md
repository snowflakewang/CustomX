<div align="center">

<h1 align="center">
  <!-- Animate Any Character in Any World -->
  CustomX: Unified Character, Action, and Scene Customization in Video World Models
</h1>

<h3 align="center">
  ECCV 2026
</h3>

<p align="center" style="font-size: 1.1em; color: #555;">
  <!-- <strong>Long-horizon world exploration with user-specified characters capable of performing open-ended actions.</strong> -->
  <strong>A framework that leverages user-specified 3D character and scene assets for long-horizon world exploration with various open-ended actions.</strong>
</p>

<div align="center">
  <a href="https://scholar.google.com/citations?user=qnOwZmkAAAAJ">Yitong Wang</a><sup>1,2*</sup>&nbsp;&nbsp;
  <a href="https://www.microsoft.com/en-us/research/people/fawe/">Fangyun Wei</a><sup>2*</sup>&nbsp;&nbsp;
  <a href="https://hongyanz.github.io/">Hongyang Zhang</a><sup>3</sup>&nbsp;&nbsp;
  <a href="https://datascience.hku.hk/people/bo-dai/">Bo Dai</a><sup>4</sup><sup>&dagger;</sup>&nbsp;&nbsp;
  <a href="https://www.microsoft.com/en-us/research/people/yanlu/">Yan Lu</a><sup>2</sup>
</div>

<p align="center" style="font-size: 0.9em; color: #666;">
  <sup>1</sup><a href="https://www.fudan.edu.cn/en/">Fudan University</a>&nbsp;&nbsp;
  <sup>2</sup><a href="https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/">Microsoft Research</a>&nbsp;&nbsp;
  <sup>3</sup><a href="https://uwaterloo.ca/">University of Waterloo</a>&nbsp;&nbsp;
  <sup>4</sup><a href="https://www.hku.hk/">The University of Hong Kong</a>
  <br>
  <small><sup>*</sup>Equal Contribution</small>
  <small><sup>&dagger;</sup>Corresponding Author</small>
</p>

<!-- <p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/arXiv-Paper-B31B1B?style=flat&labelColor=555555&logo=arxiv&logoColor=white" alt="arXiv">
  </a>
  <a href="https://snowflakewang.github.io/AniX/">
    <img src="https://img.shields.io/badge/Project-Page-4F46E5?style=flat&labelColor=555555&logo=googlechrome&logoColor=white" alt="Project Page">
  </a>
  <a href="https://github.com/snowflakewang/AniX">
    <img src="https://img.shields.io/badge/Code-Coming%20Soon-FF5722?style=flat&labelColor=555555&logo=github&logoColor=white" alt="Code Coming Soon">
  </a>
</p> -->

<p align="center">
  <a href="https://arxiv.org/abs/2512.17796"><img src="https://img.shields.io/badge/arXiv-Paper-B31B1B?style=flat&labelColor=555555&logo=arxiv&logoColor=white" alt="arXiv"></a>
  <a href="https://snowflakewang.github.io/AniX/"><img src="https://img.shields.io/badge/Project-Page-4F46E5?style=flat&labelColor=555555&logo=googlechrome&logoColor=white" alt="Project Page"></a>
  <a href="https://github.com/snowflakewang/AniX"><img src="https://img.shields.io/badge/Code-Coming%20Soon-FF5722?style=flat&labelColor=555555&logo=github&logoColor=white" alt="Code Coming Soon"></a>
</p>

</div>

---

## 📖 Abstract

Recent advances in world models have greatly enhanced interactive environment simulation. Existing methods mainly fall into two categories: (1) static world generation models, which construct 3D environments without active agents, and (2) controllable-entity models, which allow a single entity to perform limited actions in an otherwise uncontrollable environment. In this work, we introduce CustomX, leveraging the realism and structural grounding of static world generation while extending controllable-entity models to support user-specified characters capable of performing open-ended actions. Users can provide a 3DGS scene and a character, then use natural language to direct the character to perform diverse behaviors, ranging from basic locomotion to object-centric interactions, while freely exploring the environment. CustomX synthesizes temporally coherent video clips that preserve visual fidelity with the provided scene and character, formulated as a conditional autoregressive video generation problem. Built upon a pre-trained video generator, our training strategy significantly enhances motion dynamics while maintaining generalization across actions and characters. Our evaluation covers a broad range of aspects, including visual quality, character consistency, action controllability, and long-horizon coherence.

<br>

<div align="center" style="background-color: white; padding: 10px; border-radius: 5px;">
  <img src="./assets/teaser_v3.jpg" width="100%" alt="CustomX Teaser"/>
</div>

---

<p align="center">
  <small>© 2026 CustomX. Licensed under <a href="http://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a>.</small>
</p>


## 🔮 Citation
```
TBD.
```