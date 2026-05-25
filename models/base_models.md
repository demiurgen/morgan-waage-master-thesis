# Base Models

This file documents the base models used in the experiments.

The model checkpoint files are not included in this repository because they are large files and must be obtained from their original providers.

The exact checkpoint filenames are also stored inside the ComfyUI workflow JSON files in the model loader nodes.

## Static image models

### SDXL

- Model name: Stable Diffusion XL
- Model identifier: `stable-diffusion-xl-base-1.0`
- Used for: static character, background, and object generation

### SD3.5

- Model name: Stable Diffusion 3.5
- Model identifier: `stable-diffusion-3.5-large`
- Used for: static character, background, and object generation

### Flux

- Model name: FLUX.1-dev
- Model identifier: `FLUX.1-dev`
- Used for: static character, background, and object generation

## Animation models

### WAN 2.1

- Model name: WAN 2.1
- Used for: text-to-video, image-to-video, and video-to-video animation workflows

### Hunyuan

- Model name: HunyuanVideo
- Used for: text-to-video, image-to-video, and video-to-video animation workflows

### LTX 0.9.7

- Model name: LTX Video 0.9.7
- Used for: text-to-video, image-to-video, and video-to-video animation workflows

## Notes

The repository does not include checkpoint files.

Researchers who want to recreate the experiments should obtain the same or equivalent model checkpoints from the original providers.

The ComfyUI workflow JSON files contain the model filenames used in the workflow loader nodes.
