# CEPA: Context-Aware Generative Imputation for Robust Multimodal Learning in Missing Modality Scenarios

Official repository for **CEPA** (NeurIPS 2026).

Jungwon Choi, Juho Lee  
Kim Jaechul Graduate School of AI, KAIST

## Overview

CEPA predicts the representations of missing modalities for downstream prediction while mitigating representation collapse. It combines three components:

- **Adaptive masking**: learns which observed tokens to hide, so the model has to rely on the other modalities.
- **Representation prediction**: predicts the representation of a missing modality from the modalities that are present.
- **Context-conditional alignment**: keeps these predictions consistent with similar samples in which that modality is actually observed.

## Status

The code is being cleaned up and will be released in this repository soon.

## Data

**MIMIC.** The clinical experiments use MIMIC-IV, MIMIC-CXR and MIMIC-IV-Note, which require credentialed access through [PhysioNet](https://physionet.org/). We do not redistribute any MIMIC data.

**CMU-MOSEI.** CMU-MOSEI is publicly available through the [CMU Multimodal SDK](https://github.com/CMU-MultiComp-Lab/CMU-MultimodalSDK). We use the pre-extracted Wav2Vec (audio), DeBERTa (language) and MA-Net (visual) features released by [GCNet](https://github.com/zeroQiaoba/GCNet).

## Citation

```bibtex
@inproceedings{choi2026cepa,
  title     = {Context-Aware Generative Imputation for Robust Multimodal Learning in Missing Modality Scenarios},
  author    = {Choi, Jungwon and Lee, Juho},
  booktitle = {Advances in Neural Information Processing Systems},
  year      = {2026}
}
```
