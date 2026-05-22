# Workflow Overview

This folder documents the ComfyUI workflows used in the experiments.

## Static workflows

Static workflows 01-24 were used for character, background, and object generation.

The same workflow IDs were reused across all three static asset categories. The workflow structure, base model, and guidance configuration stayed the same. The asset category changed through the selected prompt and reference inputs.

## Animation workflows

Animation workflows 25-33 were used for walk-cycle generation.

These workflows tested text-to-video, image-to-video, and video-to-video generation with WAN 2.1, Hunyuan, and LTX 0.9.7.

## Workflow files

The workflow JSON files are stored in two subfolders:

- `workflows/static/`
- `workflows/animation/`
