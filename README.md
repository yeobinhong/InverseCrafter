# InverseCrafter: Efficient Video ReCapture as a Latent Domain Inverse Problem

This repository is the official implementation of InverseCrafter.

> [Yeobin Hong*](https://yeobinhong.github.io/), [Suhyeon Lee*](https://scholar.google.co.kr/citations?user=V9rMrFQAAAAJ&hl=ko), [Hyungjin Chung†](https://hyungjin-chung.github.io/), [Jong Chul Ye†](https://bispl.weebly.com/professor.html).
>
> KAIST, EverEx

[![arXiv](https://img.shields.io/badge/arXiv-2411.15540-b31b1b.svg)](https://arxiv.org/abs/2512.05672)

<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/720508eb-6113-4d53-acd5-160a71a3300d" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/69adde14-b02b-48ea-8748-8dd088faa529" controls autoplay loop></video>
     </td>
  </tr>
</table>

<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/c47f2864-5020-40f7-8f83-9b11a8eed88f" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/539f9f1d-e713-42ef-8e18-6723ce278c58" width="100%" controls autoplay loop></video>
     </td>
  </tr>
</table>

### Abstract

💡 Recent controllable 4D video generation often leverages powerful prior of Video Diffusion Models (VDMs) such as Wan, Hunyuan Video, CogVideoX.

🤔 However, existing methods rely on expensive VDM fine-tuning that risks catastrophic forgetting of generative priors, further requiring complex architectural changes and large datasets.

🚀 InverseCrafter solves this efficiently by reformulating 4D generation as an inpainting inverse problem in the latent space.

🌟 Using a principled latent mask encoding to bypass costly VAE operations, InverseCrafter achieves comparable results with near-zero computational overhead.

## Requirements

Clone this repo:
```
git clone https://github.com/yeobinhong/InverseCrafter.git
cd InverseCrafter
```

To install requirements:
```
TODO
```

## Quick Start
For video camera control, run:

**Examples**
```
TODO
```

### Efficient inference
TODO

This allows us to run InverseCrafter with a single GPU with 24GB VRAM.


## 🙏 Acknowledgements
We build upon open-source implementations of [Wan](https://github.com/Wan-Video/Wan2.1), [VideoX-Fun](https://github.com/aigc-apps/VideoX-Fun), [Reangle-A-Video](https://github.com/HyeonHo99/Reangle-Video).
