# Fine-Tuning-Stable-Diffusion

For overview of the approach and evaluation results, please refer to [Fine-tuning-approach.pdf](Fine-tuning-approach.pdf)

## Requirements
* Memory >= 16 GB
* GPU >= Nvidia T4
* Linux environment
* Note: Training scripts will not work in colab environment

## Data
* Download data from [here](https://drive.google.com/drive/folders/1OIYTrXP1WEtRhFOJItnPb129V2DFQCLF)
* Manually annotated captions for text-to-image are available in [metadata.jsonl](metadata.jsonl)
* There are 3 data files each for a specific fine-tuning task

## General Instructions
* Install diffusers
* Follow instructions provided in [Training_scripts.ipynb](Training_scripts.ipynb) for training
* For evaluation, load the [SD_Evaluation.ipynb](SD_Evaluation.ipynb) file in GPU enabled machine

## WandB Training Logs
* Text-to-image: [https://wandb.ai/areswolf/text2image-fine-tune/runs/on8sdtvi?workspace=user-abhilad1009](https://wandb.ai/areswolf/text2image-fine-tune/runs/on8sdtvi?workspace=user-abhilad1009)
* Dreambooth: [https://wandb.ai/areswolf/dreambooth-lora/runs/icne4ce2?workspace=user-abhilad1009](https://wandb.ai/areswolf/dreambooth-lora/runs/icne4ce2?workspace=user-abhilad1009)
## Demo
* Text-to-image demo: [https://huggingface.co/abhilad98/abhi_thumbsup](https://huggingface.co/abhilad98/abhi_thumbsup)
* Dreambooth demo: [https://huggingface.co/abhilad98/db_abhi](https://huggingface.co/abhilad98/db_abhi)
