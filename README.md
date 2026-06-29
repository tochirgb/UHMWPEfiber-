# UHMWPEfiber

This repository contains the computational groundwork for a processing structure
property study of compression molded UHMWPE fabric laminates.

UHMWPE fiber derives its mechanical performance from extreme molecular orientation 
(draw ratios >30). Consolidating woven fabric into a laminate requires working in 
a narrow 118–132°C window warm enough for chain interdiffusion across ply 
interfaces, cool enough to preserve orientation. This study maps that window.

What's in here:
→ Reptation model: chain interdiffusion depth vs. temperature (Arrhenius, 20 min hold)
→ Orientation model: Hermans factor and Ward affine network model across draw ratios
→ Void content and density predictions across the consolidation window
→ Peel strength prediction from diffusion depth (calibrated to Ward et al.)
→ Fabric vs. powder structural comparison
→ 6 panel publication ready figure set

Crystal structure: COD entry 1100196 (orthorhombic PE, Pnam, a=7.40 b=4.93 c=2.53 Å)
Tools: ASE, pymatgen, scipy, matplotlib all free, runs on Google Colab

Physical experiments in progress(Well it has not started yet I have planned):
Sample groups F118 / F125 / F132 (fabric, 3 temperatures) and P180 (sintered powder)
Testing: Archimedes density, T-peel (UTM), notched Charpy, drop-weight dent, 
SEM fractography (JSM-IT500) PEC Chandigarh Metallurgical lab

Paper target: NMD-ATM / Materials Today: Proceedings
