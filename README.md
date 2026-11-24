# M²F-MAE
Multi-scale and Multi-metric Fusion Masked Autoencoder

![visitors](https://visitor-badge.laobi.icu/badge?page_id=beargolden/M2F-MAE)

## Paper

This repository provides the official PyTorch implementation of M²F-MAE in the following paper:

> **Unsupervised Catenary Insulator Defect Detection via Multi-Scale Masked Reconstruction and Multi-Metric Anomaly Scoring** <br>
> Wei Xiong, Ziyun Xiong, Yueqi Yuan, Zi Qiu <br>
> Submitted to ***IEEE Transactions on Image Processing***, November 2026

Once the paper is accepted for publication, we will provide detailed instructions and release the pre-trained weight files.

Please stay tuned!

## Implementation Details

### Hardware

- GPU: NVIDIA A800-80GB PCIe (80GB)
- CPU: 14 vCPU Intel® Xeon® Gold 6348 CPU @ 2.60GHz
- MEM: 120GB

### Software

- Ubuntu: 20.04.6
- Driver: 590.48.01
- CUDA: 13.0.96
- cuDNN: 9.20.0.48
- Python: 3.12.3
- PyTorch: 2.12.1+cu130
- TorchVision: 0.27.1+cu130
- TensorBoard: 2.20.0
- OpenCV: 5.0.0

### Installation

1. Install ```uv``` with our standalone installers:

- For China mainland users:

```bash
# On macOS and Linux
curl -LsSf https://uv.agentsmirror.com/install-cn.sh | sh
```
```bash
# On Windows
powershell -ExecutionPolicy ByPass -c "irm https://uv.agentsmirror.com/install-cn.ps1 | iex"
```

- For International users:

```bash
# On macOS and Linux
curl -LsSf https://astral.sh/uv/install.sh | sh
```
```bash
# On Windows
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

2. Git clone the repository:

```bash
git clone https://github.com/beargolden/M2F-MAE.git
cd M2F-MAE
```

3. Create and activate a fast Python virtual environment:

```bash
uv venv
source .venv/bin/activate
```

4. Install dependencies:

```bash
uv pip install -r requirements.txt
```