# PINN-DVM

This repository contains the implementation of **PINN-DVM**, corresponding to:

**Linying Zhang, et al.**  
[*Simulation of rarefied gas flows using physics-informed neural network combined with discrete velocity method.*](https://doi.org/10.1063/5.0156404)

**Physics of Fluids** 35, 077124 (2023).  

---

## Purpose

PINN-DVM couples **Physics-Informed Neural Networks (PINNs)** with the **Discrete Velocity Method (DVM)** to solve the **linearized BGK equation**.  
This repo reproduces the cases reported in the paper:
- **Couette flow**
- **Fourier flow**
- **Triangular duct flow**
- **Cavity flow**

---

## Repository Usage

Each case lives in its own folder. To run a case, `cd` into that folder and execute:

```bash
python main.py
```

## Dependencies

Please install the following Python packages:

- numpy

- pandas

- matplotlib

- pyDOE

- tensorflow

### TensorFlow version per case
- **Couette flow** & **Fourier flow**: `tensorflow==1.10`  
- **Triangular duct flow** & **Cavity flow**: `tensorflow==2.1`

---

## Citation

If you use this code, please cite:

> Zhang, Linying, et al. *Simulation of rarefied gas flows using physics-informed neural network combined with discrete velocity method.* **Physics of Fluids** 35, 077124 (2023). https://doi.org/10.1063/5.0156404

**BibTeX**
```bibtex
@article{10.1063/5.0156404,
    author = {Zhang, Linying and Ma, Wenjun and Lou, Qin and Zhang, Jun},
    title = {Simulation of rarefied gas flows using physics-informed neural network combined with discrete velocity method},
    journal = {Physics of Fluids},
    volume = {35},
    number = {7},
    pages = {077124},
    year = {2023},
    month = {07},
    issn = {1070-6631},
    doi = {10.1063/5.0156404},
    url = {https://doi.org/10.1063/5.0156404},
}
```
