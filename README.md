# Single-cell ATAC-seq analysis of human embryoid bodies reveals crucial transcription factor networks involved in early germ layer specification

### Linying Li<sup>†</sup>,  Feng Zhang<sup>†</sup>, Xiaoyu He<sup>†</sup>,  ..., Junmei Zhou*, Lingjie Li*

<p align="justify">In this study, we employed human embryoid body as an in vitro model to mimic early development and conducted single-cell ATAC sequencing to delineate lineage-specific chromatin regulatory elements and their associated transcription factor (TF) networks. </p>

<p align="center">
  <img width="800"  src="https://github.com/Li-Lab2shsmu/scATAC-seq_analysis_of_human_EBs/blob/main/images/workflow.png">
</p>

# Consistency score
<p align="justify">In this study, we introduced a “consistency score” to assist cell clustering by considering both promoter and TF motif accessibility. This concept was adapted from our previously published bioinformatics tool, InferLoop (Zhang et al., 2023), which takes a matrix of peak signals and a list of predicted loops to construct a metric indicating infer loop signals, analogous to the perturbation of the Pearson correlation coefficient. In this study, we applied this framework to a matrix of gene activity and a matrix of binding activity to construct a matrix of consistency scores that reflects the contributions of TFs in individual cells. Consistency scores were computed using inferloop.calILS function, which takes gene activity matrix and binding activity matrix (chromVAR deviation scores) as inputs. The mathematical formulation underlying this calculation has been descripted in details in our published work titled “InferLoop: leveraging single-cell chromatin accessibility for the signal of chromatin loop” (Zhang et al., 2023). </p>

<p align="center">
  <img width="800"  src="https://github.com/Li-Lab2shsmu/scATAC-seq_analysis_of_human_EBs/blob/main/images/consistency%20score.png">
</p>


## About
If you have any questions, please feel free to contact Dr. Yang Dong (yang.dongau@gmail.com).

## References
1. Zhang, F. et al. InferLoop: leveraging single-cell chromatin accessibility for the signal of chromatin loop. Briefings in Bioinformatics 24(3), bbad166 (2023) 


## Citation

