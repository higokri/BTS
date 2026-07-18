<h1 align="center">BTS ⚡ Busan Token-pruning Series</h1>

<p align="center">
  As foundation models go <b>multimodal</b>, every modality drowns in redundant tokens.
  <b>B</b>usan <b>T</b>oken-pruning <b>S</b>eries is a curated collection of <b>training-free</b> token &amp; KV-cache
  pruning methods across <b>image</b>, <b>3D</b>, and <b>text</b> modalities, from the
  <a href="https://www.pnu-cvsp.com/">PNU-CVSP</a> lab.
</p>

<p align="center">
  <a href="https://higokri.github.io/BTS/"><img src="https://img.shields.io/badge/%F0%9F%8C%8E_Website-BTS-4a90d9" alt="Website"></a>
  <img src="https://img.shields.io/badge/Modalities-Image_%C2%B7_3D_%C2%B7_Text-2f6fe0" alt="Modalities">
  <img src="https://img.shields.io/badge/%E2%9A%A1_Approach-Training--free-06c29c" alt="Training-free">
  <a href="https://github.com/higokri/BTS/stargazers"><img src="https://img.shields.io/github/stars/higokri/BTS?style=social" alt="stars"></a>
</p>

<p align="center">
  🖼️ <b>Image</b> &nbsp;·&nbsp; 🧊 <b>3D</b> &nbsp;·&nbsp; 💬 <b>Text</b>
</p>

---

## 📚 Series

| | Project | Modality | Venue | Highlight | Links |
|---|---------|----------|-------|-----------|-------|
| 🖼️ | **AgilePruner** | Image | ICLR 2026 | Efficient token pruning for 2D vision models | [Page](https://paper.pnu-cvsp.com/AgilePruner/) |
| 🧊 | **3DZip** | 3D | ECCV 2026 | 94.7% performance with 128 tokens, 1.92× faster | [Page](https://paper.pnu-cvsp.com/3DZip/) · [Code](https://github.com/cvsp-lab/3DZip) |
| 💬 | **HybridKV** | Text | ICMLw 2026 | Query-agnostic KV compression, up to 36% less overhead | [Page](https://higokri.github.io/HybridKV/) · [Code](https://github.com/higokri/HybridKV) · [Paper](https://openreview.net/forum?id=sWF4OAXw7u) |

## 🎯 Overview

The **Busan Token-pruning Series** is not confined to a single modality. It shares one goal —
**⚡ prune redundant tokens without any training** for efficient inference — while each work develops its **own method**
suited to its domain: spatial grids for **3D**, attention heads for **language**, and visual tokens for **images**.
A common goal, modality-specific solutions.

## 🙏 Acknowledgements

Maintained by the [PNU-CVSP](https://www.pnu-cvsp.com/) lab, Pusan National University.
