# Pixel talking-head clips (avatar bench, 2026-11-11)

Generated on one Runpod H200 SXM ($5.29/hr) with ComfyUI + Kijai WanVideoWrapper. Voice: ElevenLabs "Candy" (eleven_v3).
Full write-up, scripts and timing table live in the private grokbot repo (infra/ai-influencer/bench-1111/RESULTS.md).

| clip | what | status | wall s | $ |
|---|---|---|---:|---:|
| pixel_it480_6s_sage.mp4 | InfiniteTalk 480p, lightx2v r64 @1.0, 6 steps, sageattn | TESTED, recommended | 86 | 0.13 |
| up_pixel_it480_svr3b_720.mp4 | above + SeedVR2 3B upscale to 720 | TESTED, recommended final | +96 | +0.14 |
| up_pixel_it480_svr3b_1080.mp4 | above + SeedVR2 3B upscale to 1080 | TESTED | +151 | +0.22 |
| up_pixel_it480_svr7b_720.mp4 | SeedVR2 7B to 720 | TESTED, no gain over 3B | +154 | +0.23 |
| pixel_it480_6s.mp4 | InfiniteTalk 480p, sdpa attention | TESTED (slower) | 111 | 0.16 |
| pixel_it720_6s_sage.mp4 | InfiniteTalk native 720p | TESTED (costly, softer) | 236 | 0.35 |
| pixel_it720_6s_sage_fp8fast.mp4 | native 720p, fp8fast (37 GB vs 51 GB VRAM) | TESTED | 237 | 0.35 |
| pixel_s2v480.mp4 / pixel_s2v480_sage.mp4 | Wan2.2 S2V Lightning 4 steps | TESTED, not default (mouth barely moves) | 55 / 45 | 0.08 / 0.07 |
| sweep/sw_*.mp4 | InfiniteTalk parameter sweep on a 4.9 s line (steps, LoRA strength, audio scale/cfg, shift, samplers, prompts, seeds) | EXPERIMENT | 44-99 | 0.07-0.15 |
