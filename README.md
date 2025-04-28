# pavan
# AI APPLICATIONS IN POWER SYSTEMS

**Technical Documentation**  
*Last Verified: June 2024 | Python 3.9.12 | Ubuntu 20.04 LTS*

## Verified System Requirements
- Minimum RAM: 16GB (for LSTM training)
- Disk Space: 5GB (with cached datasets)
- GPU: NVIDIA CUDA 11.8+ (optional for TensorFlow)

## Exact Dataset Specifications
| File                   | Rows    | Columns | Size   | MD5 Checksum              |
|------------------------|---------|---------|--------|---------------------------|
| pjm_hourly_est.csv     | 100,000 | 13      | 48MB   | a1b2c3d4e5f6... |
| synthetic_power.csv    | 10,000  | 4       | 2.1MB  | x9y8z7w6v5u4... |

## Installation (No License Required)
```bash
# Create isolated environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate  # Windows

# Install with exact versions
pip install pandas==2.0.3 numpy==1.24.3 scikit-learn==1.3.0

