# Thermal damage CEM43 computation (MIT License)
[![download](https://img.shields.io/github/downloads/jinaojakezhang/FEDFEMBioheatDamage/total.svg)](https://github.com/jinaojakezhang/FEDFEMBioheatDamage/total)
[![LICENSE](https://img.shields.io/github/license/jinaojakezhang/FEDFEMBioheatDamage.svg)](https://github.com/jinaojakezhang/FEDFEMBioheatDamage/blob/master/LICENSE)
<p align="center"><img src="https://user-images.githubusercontent.com/93865598/148063370-03703c01-2add-4f3d-8cd8-cc030739c9a0.png"></p>
This is the source repository which adds the computation of thermal damage CEM43 for the papers:

[1] Zhang, J., & Chauhan, S. (2019). Real-time computation of bio-heat transfer in the fast explicit dynamics finite element algorithm (FED-FEM) framework. Numerical Heat Transfer, Part B: Fundamentals, 75(4), 217-238. [doi:10.1080/10407790.2019.1627812](https://www.tandfonline.com/doi/abs/10.1080/10407790.2019.1627812).

[2] Zhang, J., & Chauhan, S. (2020). Fast computation of soft tissue thermal response under deformation based on fast explicit dynamics finite element algorithm for surgical simulation. Computer Methods and Programs in Biomedicine, 187, 105244. [doi:10.1016/j.cmpb.2019.105244](https://www.sciencedirect.com/science/article/abs/pii/S0169260719311344).

[3] Zhang, J., Lay, R. J., Roberts, S. K., & Chauhan, S. (2021). Towards real-time finite-strain anisotropic thermo-visco-elastodynamic analysis of soft tissues for thermal ablative therapy. Computer Methods and Programs in Biomedicine, 198, 105789. [doi:10.1016/j.cmpb.2020.105789](https://www.sciencedirect.com/science/article/abs/pii/S0169260720316229).

Please cite the above papers if you use this code for your research.

If this code is helpful in your projects, please help to :star: this repo or recommend it to your friends. Thanks:blush:
## This repository contains three source files:
- Bioheat.cpp
- BioheatDeform.cpp
-	BioheatExpan.cpp

which can be built by following the instructions in their respective repositories:
-	https://github.com/jinaojakezhang/FEDFEMBioheat
-	https://github.com/jinaojakezhang/FEDFEMBioheatDeform
-	https://github.com/jinaojakezhang/FEDFEMBioheatExpan

The only difference is that the source code files in this repository compute CEM43 and write it to a CEM43.vtk.

## How to visualize:
1.	Open CEM43.vtk. (such as using ParaView)
2.	Apply “Contour” for isosurfaces, value = 240 for 240 CEM43.
<p align="center"><img src="https://user-images.githubusercontent.com/93865598/148063372-d3184334-0748-4bd8-a27d-9720349c7c89.png"></p>

## Feedback:
Please send an email to jinao.zhang@hotmail.com. Thanks for your valuable feedback and suggestions.
