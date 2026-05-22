# LoRA Training Settings

This file documents the LoRA models used in the static asset generation workflows.

Two LoRA setups were used. The SDXL and SD3.5 workflows used the LoRA model named `lomoxl6`. The Flux workflows used the LoRA model named `lomoch`.

## SDXL and SD3.5 LoRA

### LoRA name

- Final LoRA filename/name: `lomoxl6`
- Training tool: Kohya SS
- LoRA type: Standard
- Save format: safetensors
- Mixed precision: fp16
- xFormers: enabled

### Base model

- Base model: `stabilityai/stable-diffusion-xl-base-1.0`

### Dataset setup

- Dataset size: 130 images
- Caption extension: `.txt`
- Bucket training: enabled
- Bucket no upscale: enabled
- Bucket resolution steps: 64
- Minimum bucket resolution: 256
- Maximum bucket resolution: 2048
- Latent caching: enabled
- Latent caching to disk: enabled

### Core training settings

- Maximum training steps: 1600
- Epoch setting: 20
- Batch size: 4
- Gradient accumulation steps: 1
- Optimizer: AdamW8bit
- Learning rate: 0.0001
- UNet learning rate: 0.0001
- Text encoder learning rate: 0.0001
- Learning rate scheduler: cosine
- Warmup steps: 10
- Loss type: l2
- Maximum gradient norm: 1
- Seed: 0

### LoRA network settings

- Network dimension: 256
- Network alpha: 256
- Network dropout: 0
- Rank dropout: 0
- Module dropout: 0
- Convolution dimension: 1
- Convolution alpha: 1

### Resolution

- Main training resolution: 512x512
- Additional tested resolution: 256x256

### Data augmentation and captions

- Flip augmentation: disabled
- Color augmentation: disabled
- Random crop: disabled
- Shuffle captions: disabled
- Weighted captions: disabled
- Caption dropout rate: 0

## Flux LoRA

### LoRA name

- Final LoRA filename/name: `lomoch`
- Training tool: Fluxgym
- Model type: Flux LoRA
- File format: safetensors
- Trigger words: none defined

### Base model

- Base model: `black-forest-labs/FLUX.1-dev`

### Dataset setup

- Dataset size: 130 images
- Caption extension: `.txt`
- Shuffle captions: disabled
- Keep tokens: 1
- Resolution: 1024
- Batch size: 1
- Number of repeats: 5

### License note

- The Flux LoRA was trained from `FLUX.1-dev`.
- `FLUX.1-dev` uses the FLUX.1-dev non-commercial license.
