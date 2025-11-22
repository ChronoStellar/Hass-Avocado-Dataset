Python 3.9.23

einops==0.8.1
timm==1.0.15
torch==2.7.1
torchvision==0.22.1
torchaudio==0.11.0
safetensors==0.5.3
huggingface-hub==0.33.0
coremltools==8.3.0          # only if you plan to export to Core ML
scipy==1.13.1
matplotlib==3.9.4
pillow==11.2.1
tqdm==4.67.1
PyYAML==6.0.2
numpy==1.26.4


# Best practice on Apple Silicon: use a fresh venv
python3 -m venv fastvit-env
source fastvit-env/bin/activate

# Upgrade pip first
pip install --upgrade pip

# Install everything
pip install -r requirements.txt
