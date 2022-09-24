# ROCM Stable Diffusion Docker Compose

Quick start to launch stable diffusion WebUI for AMD systems using docker-compose.

Using [AUTOMATIC1111's WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) and [basujindal's lower VRAM fork of stable diffusion](https://github.com/basujindal/stable-diffusion).

## Setup

1. Clone this repo

```bash
git clone https://github.com/WaterBread/amd-stable-diffusion-webui-docker
```

2. Download the Stable Diffusion weights from [huggingface](https://huggingface.co/CompVis/stable-diffusion-v-1-4-original) (account needed) or [here](https://drive.yerf.org/wl/?id=EBfTrmcCCUAGaQBXVIj5lJmEhjoP1tgl)
3. Place weights in this directory named `sd-v1-4.ckpt`
4. Run docker image
```bash
docker-compose up
```
5. Navigate to the WebUI: `http://127.0.0.1:7860/`
