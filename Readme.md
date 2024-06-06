# CPSAD

## Data Link
The dataset is uploaded into Google Drive, and the source data can be download in [here](https://drive.google.com/file/d/1Nasd7FhU0hqE7BzhwGm6UevbHMJjP4Ni/view?usp=sharing)

## Data Description
The data of CPSAD comes from ceramic packaging substrate samples in actual factory environments. These samples were selected during the punching hole, filling hole, and printing stage, representing actual production conditions and process changes. To ensure the accuracy and integrity of the data, we brought these samples into the laboratory environment for systematic data collection.


## Benchmark Construction

"Minimum to maximum usage of data samples and annotations" is the logic to construct our benchmarks. In order to quickly build experiments to validate the effectiveness of the CPSAD dataset, we referred to many excellent open-source frameworks. As for the scenarios without a open-source framework, we replicated these algorithm on our dataset using the corresponding GitHub source code from the references.

### Unsupervised task
We follow the pipeline of [anomalib](https://github.com/openvinotoolkit/anomalib) and [open-iad](https://github.com/M-3LAB/open-iad) to conduct our experiments about unsupervised task.

### Semi-supervised task
We follow the pipeline of [open-iad](https://github.com/M-3LAB/open-iad) to conduct our experiments about semi-supervised task.

### Zero-shot task
We have reproduced the zero-shot algorithm listed in the paper for CPSAD without referring to other publicly available frameworks.
### Few-shot task
We have reproduced the few-shot algorithm listed in the paper for CPSAD without referring to other publicly available frameworks.

### Fully-supervised task
We following the pipeline of [mmsegmentation](https://github.com/open-mmlab/mmsegmentation) to conduct our experiments about unsupervised task.

