# Preparation of FlowDrive Environment

Follow the steps below to set up the FlowDrive environment.

## 1. Clone the repository

```
git clone https://github.com/AstrixDrive/FlowDrive.git
cd FlowDrive
```

## 2. Install packages

```
conda env create --name flowdrive -f environment.yml
conda activate flowdrive
pip install -e .
pip install diffusers einops 
```
If you run into any issues during environment setup, we recommend checking the existing GitHub Issues to see if a solution has already been discussed at https://github.com/autonomousvision/navsim/issues