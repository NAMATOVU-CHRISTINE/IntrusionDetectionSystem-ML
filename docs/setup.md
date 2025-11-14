# Setup Guide

## Prerequisites
- Python 3.9 or higher
- Git
- 8GB+ RAM recommended

## Installation Steps

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd ids-ml-project
```

### 2. Create Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Install Wireshark (for traffic capture)
**Linux:**
```bash
sudo apt-get install wireshark
```

**macOS:**
```bash
brew install wireshark
```

**Windows:**
Download from https://www.wireshark.org/download.html

### 5. Verify Installation
```bash
python -c "import sklearn, pandas, numpy; print('All packages installed successfully!')"
```

## Next Steps
Proceed to Phase 2: Dataset Acquisition
- Download CICIDS2017 dataset from: https://www.unb.ca/cic/datasets/ids-2017.html
- Place files in `data/raw/` directory
