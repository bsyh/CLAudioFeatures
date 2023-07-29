# CL_AUDIO_PREDICTION

This repository is a prediction (classification) model of audio waves regarding cognitive loads (mental demands).<br>
`train.ipynb`: the trainer using `pytorch`, `torchaudio`, GPU and `CUDA`.<br>
`epoch/`: traned model stoped at some certain epochs.<br>
`ACVAffe/codes` the ACVAffe dataset downloader and dataloader for pytorch. (modified)<br>
`ACVAffe/data` the ACVAffe dataset where you'll need to download separately.



# AVCAffe
[AVCAffe](https://github.com/pritamqu/AVCAffe), data structure can be seen from [Arxiv](https://arxiv.org/abs/2205.06887).
This notebook is based on Pytorch's [speech_command_classification_with_torchaudio](https://pytorch.org/tutorials/intermediate/speech_command_classification_with_torchaudio_tutorial.html)

The data loader in this git is modified for the BioPhysics project.


# Environment setting
- install [Nvidia Driver](https://docs.nvidia.com/datacenter/tesla/tesla-installation-notes/index.html)
- install [mamba](https://mamba.readthedocs.io/en/latest/installation.html): an alternative to Conda with faster C++ implementation <br>
- install [Pytorch](https://pytorch.org): to install pytorch, please replace "conda" command with "mamba" while installing `pytorch` and `torchaudio`<br>
- run `pip install -r requirements.txt` in the repo root directory to install packages for downloader and trainer
# Usage
see in-line introduction in `train.ipynb`