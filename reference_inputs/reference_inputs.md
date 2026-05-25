# Reference Inputs

This file documents the reference inputs used in the experimental workflows.

The reference images and reference videos are not included in this repository because they contain copyrighted material or derived experiment material. This repository only documents how the inputs were used.

## Unity reference pack

The static reference material came from the Unity Asset Store package:

**2D Platformer Tileset**

Link: https://assetstore.unity.com/packages/2d/environments/2d-platformer-tileset-173155

This asset pack was used for three purposes:

- LoRA training images
- IP-Adapter style reference images
- visual reference material for the consistency assessment

The pack defined the target visual style used in the experiments. The style included bold outlines, simplified shapes, flat colors, limited shading, and a cartoon-like 2D platformer appearance.

Researchers who want to recreate the experiment need access to the same asset pack. The asset pack must be obtained through Unity Asset Store because the original files are not redistributed in this repository.

## Static asset workflows

Reference inputs were used in static workflows that included ControlNet or IP-Adapter.

### ControlNet inputs

ControlNet reference images were used to guide structure, pose, or general layout.

For character generation, the reference input defined the side-view idle pose.

For background generation, the reference input defined horizon placement and broad silhouette composition.

For object generation, the reference input defined the object structure and general shape.

### IP-Adapter inputs

IP-Adapter reference images were used to guide visual style.

The IP-Adapter reference images were selected from the Unity reference pack. These images helped align the generated outputs with the target cartoon style.

## Animation reference material

The walk-cycle motion references were based on animations from Mixamo.

Mixamo link: https://www.mixamo.com/

Mixamo was used to obtain walk-cycle motion material for the animation experiments. This motion material was used as reference input in the video-to-video workflows.

The Mixamo motion references are not included in this repository. Researchers who want to recreate the animation experiments need to obtain equivalent walk-cycle motion references from Mixamo or another legal source.

## Animation workflows

Reference inputs were used in image-to-video and video-to-video workflows.

Image-to-video workflows used a still character image as the visual reference.

Video-to-video workflows used a walk-cycle reference video to guide the movement.

The reference motion video defined the walking movement, while the character image and style guidance helped preserve the intended appearance.

## Copyright note

The reference inputs are not redistributed in this repository. The Unity asset pack and Mixamo animation material must be obtained from their original sources.

This repository documents the role of the reference inputs in the experiment, but it does not include the copyrighted source material.
