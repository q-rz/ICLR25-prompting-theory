# On the Turing completeness of prompting

[![Our paper at ICLR 2025](https://github.com/q-rz/ICLR25-prompting-theory/raw/main/assets/img.shields.io%20badge%202025-ICLR-60C332.svg)](https://openreview.net/forum?id=AS8SPTyBgw) [![Our paper on arXiv](https://github.com/q-rz/ICLR25-prompting-theory/raw/main/assets/img.shields.io%20badge%202411.01992-arXiv-B31B1B.svg)](https://arxiv.org/abs/2411.01992)

```bibtex
@inproceedings{qiu2025ask,
  title={Ask, and it shall be given: On the {Turing} completeness of prompting},
  authors={Qiu, Ruizhong and Xu, Zhe and Bao, Wenxuan and Tong, Hanghang},
  booktitle={The Thirteenth International Conference on Learning Representations},
  year={2025}
}
```

A demonstration of our constructed Transformer is in [`main.ipynb`](https://github.com/q-rz/ICLR25-prompting-theory/blob/main/main.ipynb). We provide two example tasks:

1. Computing the Parity function: the XOR of all input bits.
2. Deciding the Dyck language: balanced parenthesis sequences (`0` as `(`, `1` as `)`).

For each task, we test our construction for a few example inputs, where the constructed Transformer computes their corresponding CoTs. We extract the output answer (`output`) from each CoT and compare it with the true answer (`answer`); `AC` means that the output answer is correct. Feel free to try other inputs by modifying the `inputs` argument of the `Tester` class. 

**Note:** If you see wrong answers (`WA`) or encounter any error, please increase the precision of floating-point operations (`args.fp_round` and `args.fp_guard`).

More descriptions coming soon...
