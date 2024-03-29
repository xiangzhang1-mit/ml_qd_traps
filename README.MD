**************************************************************
QD trap data analysis

Huashan Li, 2017/07/31
updated by Yun Liu, 2018/04/17
**************************************************************

This procedure is developed to explore the relationship between various types of trap states (deep/shallow, enegetic/spatial) and QD surface passivation, targeting at identifying key structural features that are responsibile for the trap states. Specifically, it generates QD with various surface configurations, calculates their eigenvalue, and collect crucial information for further analysis with the machine learning code scikit-learn.

The data generated by VASP should be placed at the top-level folder "data".

The python3 code "qd_surface_trap_analysis.py" is designed to connect the local/global structural and electronic features. It is not completed so far, and please find the definition of descriptors in the comment lines of the script. This script import other scripts from the folder "QD_trap_py" (the module "build_feature.py" and "load_data.py" are done, yet the "trap_classify" and "trap_regress" are under development). The results should be stored in the folder "analysis-result".
