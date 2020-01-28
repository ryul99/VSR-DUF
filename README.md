# Deep Video Super-Resolution Network Using Dynamic Upsampling Filters Without Explicit Motion Compensation
Unofficial PyTorch implementation of [VSR-DUF Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jo_Deep_Video_Super-Resolution_CVPR_2018_paper.pdf)

# Setup
## Install requirements
- python3
- `pip install -r requirements.txt`

## Config
- config is written in yaml file(default: `config/default.yaml`)

# Train
- `python trainer.py -c config/path/to/file -n model_name`

## Resume training from checkpoint
- `python trainer.py -c path/to/config/file -n model_name - p path/to/checkpoint/file`

##  Reference
- https://github.com/yhjo09/VSR-DUF
- https://github.com/open-mmlab/mmsr