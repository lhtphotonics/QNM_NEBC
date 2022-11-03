# The open-source numerical tool (QNM_NEBC) of the quasinormal mode expansion theory for mesoscale plasmonic nanoresonators proposed in Ref. [1]
Reference [1] proposes a quasinormal mode (QNM) expansion theory for calculating the optical response of plasmonic nanoresonators with mesoscale (2-20 nm) feature sizes (such as the size of nanogap). The optical response of such mesoscale plasmonic nanoresonators is significantly affected by the nonlocality, surface damping and electron spill-out nonclassical quantum effects, which can be fully described by the nonclassical electromagnetic boundary condition (NEBC) expressed with the surface-response Feibelman d parameters. Using the easy-to-solve classical QNMs under classical electromagnetic boundary condition (CEBC) as a complete set of basis functions, the theory can provide rigorous expansion expressions for the source-excited nonclassical electromagnetic field and source-free nonclassical QNMs (both under the NEBC). With an analytical dependence on the non-perturbative NEBC and classical QNMs, the theory can be used as a physically intuitive and computationally efficient tool for designing mesoscale plasmonic nanoresonators.

# The softwares used in the tool
The open-source numerical tool uses COMSOL Multiphysics software to calculate the classical QNMs, and uses the MATLAB software (via the COMSOL LiveLink for MATLAB) to calculate the expansion expressions for the source-excited nonclassical electromagnetic field and source-free nonclassical QNMs.

# Codes of the tool for typical examples
The codes for producing all the curves in Figs. 2(a2) and 3(c) as typical examples in Ref. [1] are provided in the folders named “Fig2(a2)” and “Fig3(c)”, respectively, as listed in Section “3. Codes of the tool for typical examples” of the file “Read me.pdf”.

# Citing QNM_NEBC
We kindly request that you cite the following Ref. [1] in any published work for which you used our provided codes here.

# Reference
[1] Can Tao, Ying Zhong, and Haitao Liu, Quasinormal mode expansion theory for mesoscale plasmonic nanoresonators: an analytical treatment of nonclassical electromagnetic boundary condition, Physical Review Letters 129, 197401 (2022).
