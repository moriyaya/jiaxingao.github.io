---
title: "A Dual-Stream-Modulated Learning Framework for Illuminating and Super-Resolving Ultra-Dark Images"
collection: publications
category: manuscripts
permalink: /publication/2024-07-30-paper-title-number-3
excerpt: 'Enhancement of image resolution for scenes captured under extremely dim conditions represents a practical yet challenging problem that has received little attention. In such low-light scenarios, the limited lighting and minimal signal clarity tend to intensify issues such as diminished detail visibility and altered color accuracy, which are often more severe during the image enhancement process than in scenarios with adequate lighting. Consequently, standard methods for enhancing low-light images or improving their resolution, whether implemented independently or through a combined approach, generally face challenges in effectively restoring luminance, preserving color integrity, and detailing intricate features. To conquer these issues, this article introduces an innovative dual-stream (DS) modulated learning framework designed to tackle the real-world coupled degradation issues in super-resolution (SR) under low-light conditions. Leveraging natural image color characteristics, we introduce a self-regularized luminance constraint to specifically target uneven illumination. We develop illumination-semantic dual modulator (ISDM), a refinement middleware embedded in the decoding stage to bridge illumination and semantic features concurrently, aimed at safeguarding the integrity of lighting and color details at the feature level. Our approach replaces simple upsampling methods with the resolution-sensitive merging upsampler (RSMU) module, which integrates diverse sampling techniques to effectively reduce artifacts and halo effects. Comprehensive experiments on three benchmarks showcase the applicability and generalizability of our approach to diverse and challenging ultra-poorly lit settings, outperforming state-of-the-art methods with a notable improvement. The code and benchmark are publicly available at https://github.com/moriyaya/UltraIS.'
date: 2024-07-30
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (IEEE TPAMI)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://moriyaya.github.io/files/tnnls1.pdf'
citation: 'Gao J, Yue Z, Liu Y, et al. A Dual-Stream-Modulated Learning Framework for Illuminating and Super-Resolving Ultra-Dark Images[J]. IEEE Transactions on Neural Networks and Learning Systems, 2024.'
---

Enhancement of image resolution for scenes captured under extremely dim conditions represents a practical yet challenging problem that has received little attention. In such low-light scenarios, the limited lighting and minimal signal clarity tend to intensify issues such as diminished detail visibility and altered color accuracy, which are often more severe during the image enhancement process than in scenarios with adequate lighting. Consequently, standard methods for enhancing low-light images or improving their resolution, whether implemented independently or through a combined approach, generally face challenges in effectively restoring luminance, preserving color integrity, and detailing intricate features. To conquer these issues, this article introduces an innovative dual-stream (DS) modulated learning framework designed to tackle the real-world coupled degradation issues in super-resolution (SR) under low-light conditions. Leveraging natural image color characteristics, we introduce a self-regularized luminance constraint to specifically target uneven illumination. We develop illumination-semantic dual modulator (ISDM), a refinement middleware embedded in the decoding stage to bridge illumination and semantic features concurrently, aimed at safeguarding the integrity of lighting and color details at the feature level. Our approach replaces simple upsampling methods with the resolution-sensitive merging upsampler (RSMU) module, which integrates diverse sampling techniques to effectively reduce artifacts and halo effects. Comprehensive experiments on three benchmarks showcase the applicability and generalizability of our approach to diverse and challenging ultra-poorly lit settings, outperforming state-of-the-art methods with a notable improvement. The code and benchmark are publicly available at https://github.com/moriyaya/UltraIS.