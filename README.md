# RWKV Notebooks

Notebooks related to [RWKV](https://github.com/BlinkDL/RWKV-LM) – a Parallelizable RNN

## Fine-tuning:

The goal for these notebooks is to simplify fine-tuning of the RWKV models trained by [BlinkDL](https://github.com/BlinkDL) on the Pile

With small changes you should be able to train/tune any RWKV model

### [RWKV-v2](https://colab.research.google.com/github/resloved/RWKV-notebooks/blob/master/RWKV_v2_RNN_Pile_Fine_Tuning.ipynb) and [RWKV-v3](https://colab.research.google.com/github/resloved/RWKV-notebooks/blob/master/RWKV_v3_RNN_Pile_Fine_Tuning.ipynb)

Only necessary for fine-tuning legacy models

### [RWKV-v4](https://colab.research.google.com/github/resloved/RWKV-notebooks/blob/master/RWKV_v4_RNN_Pile_Fine_Tuning.ipynb)

Edits training files to attempt to stay up to date to changes to the RWKV repo, may cause unexpected instability

### [RWKV-v4neo](https://colab.research.google.com/github/resloved/RWKV-notebooks/blob/master/RWKV_v4neo_Fine_Tuning.ipynb)

Most stable option using the latest command line interface for training

### [RWKV-LoRA](https://colab.research.google.com/github/resloved/RWKV-notebooks/blob/master/RWKV_LoRA.ipynb)

Uses the [LoRA fork](https://github.com/Blealtan/RWKV-LM-LoRA) of RWKV by [Blealtan](https://github.com/Blealtan)

Requires less VRAM and is recommended for most fine-tuning tasks
