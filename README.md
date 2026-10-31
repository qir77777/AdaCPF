# AdaCPF: Cross-Channel Priors for Adaptive Underwater Image Enhancement

AdaCPF uses shared cross-channel and frequency cues to guide adaptive underwater image enhancement. This repository presents the framework and visual results.

## Method

The image-frequency prior encoder (IFPE) extracts shared degradation cues. IACSM conditions low-frequency spectral modulation, while the attenuation-aware residual gate (AARG) controls spatial and channel-wise corrections. The color-aware fidelity loss (CAFL) guides training.

![AdaCPF framework](figures/framework.jpg)

### Core modules

![Core modules](figures/core_modules.jpg)

## Visual results

![Component responses](figures/feature_responses.jpg)
![Visual comparison 1](figures/visual_comparison_1.jpg)
![Visual comparison 2](figures/visual_comparison_2.jpg)
![Real-world results](figures/real_world_results.jpg)

## Underwater video

[Enhanced test2 video](video/test2_enhanced.mp4): output of the third complete processing run of the self-captured underwater sequence, with 473 frames at 256 × 256 resolution. Playback rate and measured processing throughput are different quantities.

On Jetson Orin NX SUPER 16 GB, the three complete-video processing runs achieved 19.080, 19.019, and 19.118 frames per second, including decoding and encoding.

## Repository contents

This repository provides the architecture illustrations and visual demonstration materials.

