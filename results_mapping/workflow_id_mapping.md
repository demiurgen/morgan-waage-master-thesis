# Workflow ID Mapping

This file maps the workflow IDs used in the thesis to the uploaded ComfyUI workflow files.

## Static asset workflows

Static workflows 01-24 were reused for character, background, and object generation. The workflow file stayed the same across these three asset categories. The asset category changed through the selected prompt and reference inputs.

| Thesis workflow ID | Workflow file | Type | Guidance technique | Base model |
|---|---|---|---|---|
| 1 | `workflows/static/workflow_01.json` | Static | Text-to-Image only | SDXL |
| 2 | `workflows/static/workflow_02.json` | Static | Text-to-Image only | SD3.5 |
| 3 | `workflows/static/workflow_03.json` | Static | Text-to-Image only | Flux |
| 4 | `workflows/static/workflow_04.json` | Static | Text-to-Image + LoRA | SDXL |
| 5 | `workflows/static/workflow_05.json` | Static | Text-to-Image + LoRA | SD3.5 |
| 6 | `workflows/static/workflow_06.json` | Static | Text-to-Image + LoRA | Flux |
| 7 | `workflows/static/workflow_07.json` | Static | Text-to-Image + ControlNet | SDXL |
| 8 | `workflows/static/workflow_08.json` | Static | Text-to-Image + ControlNet | SD3.5 |
| 9 | `workflows/static/workflow_09.json` | Static | Text-to-Image + ControlNet | Flux |
| 10 | `workflows/static/workflow_10.json` | Static | Text-to-Image + IP-Adapter | SDXL |
| 11 | `workflows/static/workflow_11.json` | Static | Text-to-Image + IP-Adapter | SD3.5 |
| 12 | `workflows/static/workflow_12.json` | Static | Text-to-Image + IP-Adapter | Flux |
| 13 | `workflows/static/workflow_13.json` | Static | Text-to-Image + LoRA + ControlNet | SDXL |
| 14 | `workflows/static/workflow_14.json` | Static | Text-to-Image + LoRA + ControlNet | SD3.5 |
| 15 | `workflows/static/workflow_15.json` | Static | Text-to-Image + LoRA + ControlNet | Flux |
| 16 | `workflows/static/workflow_16.json` | Static | Text-to-Image + LoRA + IP-Adapter | SDXL |
| 17 | `workflows/static/workflow_17.json` | Static | Text-to-Image + LoRA + IP-Adapter | SD3.5 |
| 18 | `workflows/static/workflow_18.json` | Static | Text-to-Image + LoRA + IP-Adapter | Flux |
| 19 | `workflows/static/workflow_19.json` | Static | Text-to-Image + ControlNet + IP-Adapter | SDXL |
| 20 | `workflows/static/workflow_20.json` | Static | Text-to-Image + ControlNet + IP-Adapter | SD3.5 |
| 21 | `workflows/static/workflow_21.json` | Static | Text-to-Image + ControlNet + IP-Adapter | Flux |
| 22 | `workflows/static/workflow_22.json` | Static | Text-to-Image + LoRA + ControlNet + IP-Adapter | SDXL |
| 23 | `workflows/static/workflow_23.json` | Static | Text-to-Image + LoRA + ControlNet + IP-Adapter | SD3.5 |
| 24 | `workflows/static/workflow_24.json` | Static | Text-to-Image + LoRA + ControlNet + IP-Adapter | Flux |

## Animation workflows

Animation workflows 25-33 were used for walk-cycle generation.

| Thesis workflow ID | Workflow file | Type | Generation mode | Base model |
|---|---|---|---|---|
| 25 | `workflows/animation/workflow_25.json` | Animation | Text-to-Video | WAN 2.1 |
| 26 | `workflows/animation/workflow_26.json` | Animation | Text-to-Video | Hunyuan |
| 27 | `workflows/animation/workflow_27.json` | Animation | Text-to-Video | LTX 0.9.7 |
| 28 | `workflows/animation/workflow_28.json` | Animation | Image-to-Video | WAN 2.1 |
| 29 | `workflows/animation/workflow_29.json` | Animation | Image-to-Video | Hunyuan |
| 30 | `workflows/animation/workflow_30.json` | Animation | Image-to-Video | LTX 0.9.7 |
| 31 | `workflows/animation/workflow_31.json` | Animation | Video-to-Video | WAN 2.1 |
| 32 | `workflows/animation/workflow_32.json` | Animation | Video-to-Video | Hunyuan |
| 33 | `workflows/animation/workflow_33.json` | Animation | Video-to-Video | LTX 0.9.7 |
