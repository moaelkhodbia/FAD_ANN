This repository contains the data used in the publication titled "Integrating Machine Learning in Failure Assessment Diagram Methodology for Enhanced Tubular Structures Integrity Evaluation".

Citation

If you use this data in your research, please cite the following publication:

[Insert citation information for your publication here]
Data Description

The data is stored in the FADs1.rar and FADs2.rar files. These files contain 1440 text files (.txt) in the following format:

FAD_X1_X2_X3_X4_X5.txt

X1: Crack type or case number (e.g., 1, 2, ...)
X2: Crack depth to wall thickness ratio (a/t)
X3: Residual stress percentage
X4: Material name (e.g., P110, L80, K55)
X5: Wall thickness to inner radius ratio (t/Ri)
Content of Text Files

Each text file contains data in the following format:

8 Columns:
Load: the applied load magnitude.
Lr: load ratio (load normalized by the limit load).
J_pe: elastic J-integral due to primary loading.
J_p: elastic-plastic J-integral due to primary loading.
J_ps: elastic-plastic J-integral due to both primary and secondary loading.
Phi: a multiplication factor used to quantify the impact of secondary stresses.
K_r:  stress intensity ratio incorporating residual stress effects.
K_r (original): K_r:  stress intensity ratio without residual stress effects.

Last Row (4 columns):
P_L: limit load.
J_se: elastic J-integral due to secondary loading.
J_s: elastic-plastic J-integral due to secondary loading.
Phi_0: an initial value of Phi that is used to calculate Phi.

Further Information

For any questions or further information regarding the data or its usage, please contact Mohamed Elkhodbia at 100060498@ku.ac.ae.