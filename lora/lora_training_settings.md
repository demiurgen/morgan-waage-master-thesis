# LoRA Training Settings

This file documents the LoRA training settings available from the Kohya SS configuration files used during LoRA preparation.

The LoRA model used in the experiments was named `lomoxl6`. The available configuration files document the training setup used for LoRA preparation. These settings were used as the basis for the LoRA training process for the SDXL and SD3.5 workflows.

## Training tool

- Training tool: Kohya SS
- LoRA type: Standard
- Save format: safetensors
- Mixed precision: fp16
- xFormers: enabled

## Base model

- Base model: `stabilityai/stable-diffusion-xl-base-1.0`

## Dataset setup

- Training data directory: `C:/Users/demiurgen/Desktop/LoRA/img`
- Caption extension: `.txt`
- Bucket training: enabled
- Bucket no upscale: enabled
- Bucket resolution steps: 64
- Minimum bucket resolution: 256
- Maximum bucket resolution: 2048
- Latent caching: enabled
- Latent caching to disk: enabled

## Core training settings

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

## LoRA network settings

- Network dimension: 256
- Network alpha: 256
- Network dropout: 0
- Rank dropout: 0
- Module dropout: 0
- Convolution dimension: 1
- Convolution alpha: 1

## Resolution

Available configuration files show two tested resolutions:

- 512x512
- 256x256

The main LoRA preparation configuration used 512x512 resolution.

## Data augmentation and captions

- Flip augmentation: disabled
- Color augmentation: disabled
- Random crop: disabled
- Shuffle captions: disabled
- Weighted captions: disabled
- Caption dropout rate: 0

## Output

- Output directory: `C:/Users/demiurgen/Desktop/LoRA/model`
- Output name in the available Kohya configuration: `last`
- Final LoRA filename used in the experiments: `lomoxl6`

- # Flux LoRA Training Settings

This section documents the Flux LoRA used in the Flux workflows.

## LoRA name

- Final LoRA filename/name: `lomoch`
- Training tool: Fluxgym
- Base model: `black-forest-labs/FLUX.1-dev`
- Model type: Flux LoRA
- File format: safetensors
- Trigger words: none defined

## Dataset setup

- Dataset folder: `C:\Users\demiurgen\fluxgym\datasets\lomoch`
- Caption extension: `.txt`
- Shuffle captions: disabled
- Keep tokens: 1
- Resolution: 1024
- Batch size: 1
- Number of repeats: 5

## License note

The base model was FLUX.1-dev, which uses the FLUX.1-dev non-commercial license.
