# MPC-Tuning: Hybrid Optimization for Model Predictive Controllers

## 📖 Overview
This repository contains the source code for **MPC-Tuning**, developed by **Sergio A. C. Giraldo (principal), Príamo A. Melo, and Argimiro R. Secchi** at the **Laboratory of Software Development for Process Control and Optimization (LADES)**, affiliated with the **Programa de Engenharia Química (PEQ), Universidade Federal do Rio de Janeiro (UFRJ).**

The purpose of this project is to provide **a hybrid tuning methodology for Model Predictive Controllers (MPC)**, which optimizes both continuous and discrete tuning parameters to improve control performance while reducing computational effort.

This repository serves as a resource for **researchers, control engineers, and practitioners** working in **process control, predictive modeling, and automation**.

## 🚀 Features
- Hybrid tuning method for MPC optimization.
- Implementation with MATLAB's Model Predictive Control Toolbox.
- Support for both **linear and nonlinear systems**.
- Code adapted for practical applications and industrial simulations.

## 📦 Installation
To install and use this project, follow these steps:

### Prerequisites
Ensure you have the following dependencies installed:
```bash
# Required MATLAB Toolbox:
MATLAB Model Predictive Control Toolbox
```

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/LADES-PEQ/MPC-Tuning.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MPC-Tuning
   ```
3. Open MATLAB and add the project path:
   ```matlab
   addpath(genpath('MPC-Tuning'))
   ```
4. Run an example:
   ```matlab
   run('MPC-Tuning/Examples/Example1.m')
   ```
5. (Optional) Modify parameters in `mpc_tuning.m` to adapt the optimization to your system.

## 📂 Repository Structure
```
├── MPC-Tuning/           # Core tuning algorithms
└── DTC-GPC/              # Example implementation of DTC-GPC
└── Explicit-NMPC/        # Explicit Nonlinear MPC cases
└── Matlab-Toolbox/       # MPC examples using the MPC Toolbox - Matlab
```

## ✏️ Authors & Contributors
This project was developed by:

- **Sergio A. C. Giraldo** - Principal Researcher - sergio@peq.coppe.ufrj.br
- **Príamo A. Melo** - Research Collaborator
- **Argimiro R. Secchi** - Research Supervisor

We welcome contributions!.

## 🔬 References & Publications
If you use this work in your research, please cite the following publication:

- **Sergio A. C. Giraldo, Príamo A. Melo, and Argimiro R. Secchi**.  
  **"Tuning of Model Predictive Controllers Based on Hybrid Optimization"**,  
  *Processes*, vol. 10, no. 2, 2022.  
  [DOI: 10.3390/pr10020351](https://www.mdpi.com/2227-9717/10/2/351)

### **BibTeX Citation**
```bibtex
@article{Giraldo2022,
  author  = {Giraldo, Sergio A. C. and Melo, Príamo A. and Secchi, Argimiro R.},
  title   = {Tuning of Model Predictive Controllers Based on Hybrid Optimization},
  journal = {Processes},
  volume  = {10},
  year    = {2022},
  number  = {2},
  article-number = {351},
  url     = {https://www.mdpi.com/2227-9717/10/2/351},
  issn    = {2227-9717},
  doi     = {10.3390/pr10020351}
}
```

## 🛡 License
This work is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0) License**.
You are free to:
- **Use, modify, and distribute** this code for any purpose.
- **Cite the following reference** when using this code:
  
  **Sergio A. C. Giraldo, Príamo A. Melo, and Argimiro R. Secchi**.  
  **"Tuning of Model Predictive Controllers Based on Hybrid Optimization"**,  
  *Processes*, vol. 10, no. 2, 2022.  
  [DOI: 10.3390/pr10020351](https://www.mdpi.com/2227-9717/10/2/351)

See the full license details in the [LICENSE](LICENSE) file.


## 📞 Contact
For inquiries or collaborations, please contact **Sergio A. C. Giraldo** at **sergio@peq.coppe.ufrj.br** or open an issue in this repository.

## ⭐ Acknowledgments
 - We acknowledge the support of the **LADES Research Group**, **PEQ - UFRJ**, and all contributors.
 - This research was funded by the National Council for Scientific and Technological Development (CNPq) and the Brazilian Coordination for the Improvement of Higher Education Personnel (CAPES).

