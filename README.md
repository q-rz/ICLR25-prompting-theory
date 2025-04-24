# Turing completeness of prompting

The implementation of the constructed Transformer is in `main.ipynb`. We provide two example tasks:

1. Computing the Parity function: the XOR of all input bits.
2. Deciding the Dyck language: balanced parenthesis sequences (`0` as `(`, `1` as `)`).

For each task, we provide 10 example inputs; the Transformer will compute their corresponding CoTs. Feel free to try other inputs by modifying the `inputs` argument of the `Tester` class. 

**Note:** If you see wrong answers (`WA`), please increase the precision of floating-point operations (`args.fp_round` and `args.fp_guard`).

More descriptions coming soon...
