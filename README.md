# ac_study

## Migration of rotary position embedding (Pytorch -> triton)

---
## Anaconda environment
```
CONTAINER_NAME="ac_study"
conda create -n ${CONTAINER_NAME} -c conda-forge python=3.10 cudatoolkit=11.8
conda activate ${CONTAINER_NAME}
conda install -c conda-forge cudnn=8.8.0

pip install numpy==1.24.1 torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

pip install numpy==1.24.1 notebook==6.5.5 traitlets==5.9.0
```