# α-Synuclein C-terminal teaching trajectory

Protein-only PDB topology and stride-100 DCD supplied by Paul Robustelli for the class Cα-position tICA exercise. The trajectory contains 5,555 stored frames and 20 Cα atoms (residues 121–140).

The stated trajectory duration is approximately 200 μs. The notebook uses 200 μs / 5,555 ≈ 36.004 ns per stored frame. The stride is already included; do not multiply this spacing by 100 again.

The notebook `notebooks/ASyn_Calpha_TICA.ipynb` downloads these files automatically. These are trajectory coordinates, not precomputed tICA results.

SHA-256 checksums:

- `asyn_Cterm_apo.proteinonly.s100.dcd`: `46ee4d6f27ba2fb4ff3e37f168526bd049b0a2551ef4c0f659d5e28203587467`
- `asyn_Cterm_apo.proteinonly.pdb`: `37dc62f1aa4acb8880d81e6114881447780e607cc969f2bdac527119237b8009`
