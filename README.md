# LiteIE: Towards Lightest Low-Light Image Enhancement Architecture for Mobile Devices

[![Paper](https://img.shields.io/badge/arXiv-2507.04277-b31b1b.svg)](https://arxiv.org/abs/2507.04277)
[![Elsevier Journal](https://img.shields.io/badge/Expert%20Systems%20with%20Applications-In%20Press-blue.svg)](https://doi.org/10.1016/j.eswa.2025.129125)

LiteIE is an ultra-lightweight, real-time low-light image enhancement framework specifically designed for mobile and embedded devices. This repository provides the official resources for the paper [Towards Lightest Low-Light Image Enhancement Architecture for Mobile Devices](https://arxiv.org/abs/2507.04277).

---

## Highlights

1. **Ultra-light backbone:**  
   We design a network-agnostic feature extractor that uses only two convolutions (58 weights in total) to produce a compact enhancement tensor.

2. **Parameter-free Iterative Restoration Module (IRM):**  
   IRM reuses previously extracted features to progressively recover fine details lost in earlier enhancement steps, without introducing any additional learnable parameters.

3. **Multi-Scale Color Consistency Loss:**  
   To ensure stable and natural enhancement, we design MSCol Loss, which preserves local color structure while maintaining global color balance.

4. **Extensive validation:**  
   LiteIE generalizes well across diverse low-light datasets and runs efficiently on mobile SoCs, enabling fast inference on resource-limited devices.

---

## Note on Code Release

We are actively working on further research and projects based on LiteIE. The code will be released after subsequent related works are completed, in order to provide a more comprehensive and robust package for the community.  
Stay tuned for updates!

---

## Paper Info

- **Title:** Towards Lightest Low-Light Image Enhancement Architecture for Mobile Devices
- **Authors:** Guangrui Bai, Hailong Yan, Wenhai Liu, Yahui Deng, Erbao Dong
- **Journal:** Expert Systems with Applications (Elsevier), In Press
- **arXiv:** [2507.04277](https://arxiv.org/abs/2507.04277)
- **DOI:** [10.1016/j.eswa.2025.129125](https://doi.org/10.1016/j.eswa.2025.129125)

---

## Citation

If you find this project helpful in your research, please cite our paper:

```bibtex
@article{LiteIE2025,
  title={Towards Lightest Low-Light Image Enhancement Architecture for Mobile Devices},
  author={Guangrui Bai and Hailong Yan and Wenhai Liu and Yahui Deng and Erbao Dong},
  journal={Expert Systems with Applications},
  year={2025},
  doi={10.1016/j.eswa.2025.129125},
  eprint={2507.04277},
  archivePrefix={arXiv}
}
```

---

## Contact

- Author: [mubaisam](https://github.com/mubaisam)
- Issues: [LiteIE Issues](https://github.com/mubaisam/LiteIE/issues)
- Paper: [arXiv](https://arxiv.org/abs/2507.04277)

---

## License

This project is licensed under the Apache-2.0 License.

---

Star, fork, or open an issue to help us improve LiteIE!
