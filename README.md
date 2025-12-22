\# Towards Equitable Diagnosis of Rare Cardiac Diseases in Electrocardiograms via Anomaly Detection Pretraining

This is an official implementation of “Towards Equitable Diagnosis of Rare Cardiac Diseases in Electrocardiograms via Anomaly Detection Pretraining” with PyTorch

\*\*Abstract\*\*:  Rare cardiac anomalies are difficult to detect from electrocardiograms (ECGs) because of their long-tailed distribution with extremely limited case counts and demographic disparities in diagnostic performance. These limitations contribute to delayed recognition and uneven quality of care. A generalizable framework that can enhance sensitivity while ensuring equity across diverse populations is urgently needed. We developed an AI-assisted ECG framework integrating self-supervised anomaly detection with demographic-aware representation learning. The system was trained on over one million ECGs, externally validated across multiple cohorts, and prospectively evaluated in an emergency department setting. Deployment feasibility was demonstrated through CPU-based optimization. Evaluated on a longitudinal cohort of over one million clinical ECGs, the proposed model achieved an AUROC of 94.7% for rare anomalies and reduced the common–rare performance gap by 73%, while maintaining consistent diagnostic performance across age and sex groups. External validation across multiple cohorts and a prospective emergency department study confirmed its clinical utility: clinician sensitivity to rare anomalies increased by 24.5\\%, and time-to-diagnosis was shortened by 36 seconds per case. The framework also provided interpretable anomaly localization (AUROC 76.5%) that aligned with physician assessments, supporting integration into routine clinical workflows. This equity-aware AI framework demonstrates scalable performance for rare cardiac anomaly detection and mitigates diagnostic disparities across populations. Beyond ECGs, the approach provides a generalizable paradigm for equitable anomaly detection in biomedical signals, underscoring its potential to advance digital health and global health equity.

\## Get Started

\### Environment
\- numpy==1.22.4  
\- pandas==1.1.3  
\- Pillow==8.4.0  
\- torch==1.10.1  
\- scipy==1.7.3  
\- heartpy==1.2.7

\### Checkpoint
Download the ckpt from https://drive.google.com/file/d/1E4NuKirypMk\_Uy6iHenkUfP9cNEtvJi7/view?usp=sharing and put it under `model\_template/weights/`

\### Quick Start
Run test.py for evaluation on the given data
Run train.py for training

If our work is helpful for your research, please consider citing:

```
@inproceedings{huang2025towards,
  title={Towards Equitable Diagnosis of Rare Cardiac Diseases in Electrocardiograms via Anomaly Detection Pretraining}
  author={Huang, Chaoqin and Jiang, Aofan and Cao, Qing and Xu, Yuchen and Zeng, Zi and Chen, Kang and Chi, Chenfei and Wang, Yanfeng and Zhang, Ya},
  year={2025}
}
```

