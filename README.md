# Pixel

Pixel is a cute chibi calico cat, drawn as a future mascot in a clean cartoon / sticker style.

This repo is a public reference pack: a turnaround, an expression sheet, pose illustrations, and a sticker sheet. Use them as character guides for stories, animations, merch concepts, and later 3D work.

**These images are AI-generated concepts**, produced from the original FRONT / SIDE / TOP / BOTTOM turnaround in [`reference/pixel-turnaround-original.jpg`](reference/pixel-turnaround-original.jpg). They are not a finished brand kit. When markings disagree, trust the original turnaround.

![Pixel contact sheet](contact-sheet.jpg)

## Character bible

| | |
| --- | --- |
| **Name** | Pixel |
| **Species** | Cat (calico) |
| **Style** | Clean cartoon / die-cut sticker illustration |
| **Proportions** | Chibi: large head, short rounded body, small paws |
| **Personality (visual)** | Friendly, curious, a little mischievous, always cute |

### Colors

Approximate hex values sampled from the original turnaround:

| Swatch | Role | Hex |
| --- | --- | --- |
| White | Fur (face, chest, belly, paws) and background | `#FFFFFF` |
| Black | Patches and outlines | `#1C1B1B` |
| Orange | Calico patches and speckles | `#F4A068` |
| Yellow-green | Eye iris | `#B6C371` |
| Salmon | Inner ears | `#E09072` |
| Pink | Nose | `#F39598` |
| Pink | Toe beans / paw pads | `#F69B98` |

### Markings

Keep these consistent in every view:

- White face with a **white blaze** down the center of the forehead
- **Black patches** around both eyes and across the top of the head, with **tiny orange speckles** in the black
- A few **orange patches** on the cheeks / forehead, matching the original front view
- **Pink inner ears**, black outer ear fur
- Small **pink triangle nose**, tiny simple smiling mouth
- **Big round yellow-green eyes** with large dark pupils and a small white highlight
- **White chest, belly, and paws**
- Asymmetrical **orange and black calico patches** on the shoulders, back, and flanks
- **Fluffy tail**, black with orange speckles and orange patches, often curled around the body
- **Pink toe beans** whenever the paw pads are visible (wave, jump, bottom view)

### Style rules

- Thick, even black outlines
- Flat colors; no realistic fur, no heavy airbrushed shading
- Plain white background unless a simple prop is part of the pose (laptop, mug, a ledge)
- No extra characters, logos, or watermarks
- The original turnaround is the source of truth for the patch layout

## Gallery

### Original reference

The source sheet Justin provided: front, side, top, and bottom.

[![Original turnaround](reference/pixel-turnaround-original.jpg)](reference/pixel-turnaround-original.jpg)

### Turnaround

Front, three-quarter, side, and back sitting views.

[![Turnaround sheet](turnaround/pixel-turnaround-sheet.jpg)](turnaround/pixel-turnaround-sheet.jpg)

### Expressions

Happy, sleepy, surprised, angry, love (heart eyes), and cry-laugh.

[![Expression sheet](expressions/pixel-expression-sheet.jpg)](expressions/pixel-expression-sheet.jpg)

### Poses

| Waving | Sleeping | Stretching | Loaf | Jumping |
| --- | --- | --- | --- | --- |
| [![Waving](poses/pixel-pose-waving.jpg)](poses/pixel-pose-waving.jpg) | [![Sleeping](poses/pixel-pose-sleeping.jpg)](poses/pixel-pose-sleeping.jpg) | [![Stretching](poses/pixel-pose-stretching.jpg)](poses/pixel-pose-stretching.jpg) | [![Loaf](poses/pixel-pose-loaf.jpg)](poses/pixel-pose-loaf.jpg) | [![Jumping](poses/pixel-pose-jumping.jpg)](poses/pixel-pose-jumping.jpg) |

| Laptop | Coffee | Peace | Peeking | Running |
| --- | --- | --- | --- | --- |
| [![Laptop](poses/pixel-pose-laptop.jpg)](poses/pixel-pose-laptop.jpg) | [![Coffee](poses/pixel-pose-coffee.jpg)](poses/pixel-pose-coffee.jpg) | [![Peace](poses/pixel-pose-peace.jpg)](poses/pixel-pose-peace.jpg) | [![Peeking](poses/pixel-pose-peeking.jpg)](poses/pixel-pose-peeking.jpg) | [![Running](poses/pixel-pose-running.jpg)](poses/pixel-pose-running.jpg) |

### Stickers

A merch-style sticker pack with a white die-cut border on each pose.

[![Sticker sheet](stickers/pixel-sticker-sheet.jpg)](stickers/pixel-sticker-sheet.jpg)

## Repo layout

```
reference/     original FRONT / SIDE / TOP / BOTTOM turnaround
turnaround/    generated front, three-quarter, side, back sheet
expressions/   generated expression sheet
poses/         individual pose illustrations
stickers/      sticker-pack sheet
contact-sheet.jpg
prompts.md     exact generation prompts, for reproducibility
```

## Notes

- The expression sheet and the loaf pose were each generated a second time. The first expression sheet had a weak cry-laugh (a wink instead of tears of joy). The first loaf still showed front paws, so it read as a sit rather than a true loaf. The finals in this repo are the second passes.
- Patch shapes drift a little from pose to pose, which is expected for image generation. Use the original turnaround when you need a strict marking match.
- The peeking pose uses a thin ledge line rather than a solid wall.
- Exact prompts are in [`prompts.md`](prompts.md).
