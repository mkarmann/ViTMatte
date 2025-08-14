# Installation

ViTMatte stuff
```bash
conda create -n ViTMatte python==3.8.8
conda activate ViTMatte
cd path/to/ViTMatte
pip install -r requriments.txt
```

Had to update pytorch for detectron2 to work
```bash
pip3 install torch torchvision --upgrade
```

Then get detectron 2
```bash
cd path/to/general/repositories
git clone https://github.com/facebookresearch/detectron2.git
python -m pip install -e detectron2
```