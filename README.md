<h1 align='center'>EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditioning</h1>

<div align='center'>
    <a href='https://github.com/yuange250' target='_blank'>Zhiyuan Chen</a><sup>*</sup>&emsp;
    <a href='https://github.com/JoeFannie' target='_blank'>Jiajiong Cao</a><sup>*</sup>&emsp;
    <a href='https://github.com/octavianChen' target='_blank'>Zhiquan Chen</a><sup></sup>&emsp;
    <a href='https://lymhust.github.io/' target='_blank'>Yuming Li</a><sup></sup>&emsp;
    <a href='https://github.com/' target='_blank'>Chenguang Ma</a><sup></sup>
</div>
<div align='center'>
    *Equal Contribution.
</div>

<div align='center'>
Terminal Technology Department, Alipay, Ant Group.
</div>
<br>
<div align='center'>
    <a href='https://antgroup.github.io/ai/echomimic/'><img src='https://img.shields.io/badge/Project-Page-blue'></a>
    <a href='https://huggingface.co/BadToBest/EchoMimic'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Model-yellow'></a>
    <a href='https://huggingface.co/spaces/BadToBest/EchoMimic'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Demo-yellow'></a>
    <a href='https://www.modelscope.cn/models/BadToBest/EchoMimic'><img src='https://img.shields.io/badge/ModelScope-Model-purple'></a>
    <a href='https://www.modelscope.cn/studios/BadToBest/BadToBest'><img src='https://img.shields.io/badge/ModelScope-Demo-purple'></a>
    <a href='https://arxiv.org/abs/2407.08136'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a>
</div>

## &#x1F680; EchoMimic Series
* EchoMimicV1: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditioning. [GitHub](https://github.com/antgroup/echomimic)
* EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation. [GitHub](https://github.com/antgroup/echomimic_v2)
* EchoMimicV3: 1.3B Parameters are All You Need for Unified Multi-Modal and Multi-Task Human Animation. [GitHub](https://github.com/antgroup/echomimic_v3)

## &#x1F4E3; Updates
* [2024.12.10] 🔥 EchoMimic is accepted by AAAI 2025.
* [2024.11.21] 🔥🔥🔥 We release our [EchoMimicV2](https://github.com/antgroup/echomimic_v2) codes and models.
* [2024.08.02] 🔥 EchoMimic is now available on [huggingface](https://huggingface.co/spaces/BadToBest/EchoMimic) with A100 GPU. Thanks Wenmeng Zhou@ModelScope.
* [2024.07.25] 🔥🔥🔥 Accelerated models and pipe on **Audio Driven** are released. The inference speed can be improved by **10x** (from ~7mins/240frames to ~50s/240frames on V100 GPU)
* [2024.07.23] 🔥 EchoMimic gradio demo on [modelscope](https://www.modelscope.cn/studios/BadToBest/BadToBest) is ready.
* [2024.07.23] 🔥 EchoMimic gradio demo on [huggingface](https://huggingface.co/spaces/fffiloni/EchoMimic) is ready. Thanks Sylvain Filoni@fffiloni.
* [2024.07.17] 🔥🔥🔥 Accelerated models and pipe on **Audio + Selected Landmarks** are released. The inference speed can be improved by **10x** (from ~7mins/240frames to ~50s/240frames on V100 GPU)
* [2024.07.14] 🔥 [ComfyUI](https://github.com/smthemex/ComfyUI_EchoMimic) is now available. Thanks @smthemex for the contribution. 
* [2024.07.13] 🔥 Thanks [NewGenAI](https://www.youtube.com/@StableAIHub) for the [video installation tutorial](https://www.youtube.com/watch?v=8R0lTIY7tfI).
* [2024.07.13] 🔥 We release our pose&audio driven codes and models.
* [2024.07.12] 🔥 WebUI and GradioUI versions are released. We thank @greengerong @Robin021 and @O-O1024 for their contributions.
* [2024.07.12] 🔥 Our [paper](https://arxiv.org/abs/2407.08136) is in public on arxiv.
* [2024.07.09] 🔥 We release our audio driven codes and models.

## &#x1F305; Gallery
### Audio Driven (Sing)

<table class="center">
    
<tr>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/d014d921-9f94-4640-97ad-035b00effbfe" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/877603a5-a4f9-4486-a19f-8888422daf78" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/e0cb5afb-40a6-4365-84f8-cb2834c4cfe7" muted="false"></video>
    </td>
</tr>

</table>

### Audio Driven (English)

<table class="center">
    
<tr>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/386982cd-3ff8-470d-a6d9-b621e112f8a5" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/5c60bb91-1776-434e-a720-8857a00b1501" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/1f15adc5-0f33-4afa-b96a-2011886a4a06" muted="false"></video>
    </td>
</tr>

</table>

### Audio Driven (Chinese)

<table class="center">
    
<tr>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/a8092f9a-a5dc-4cd6-95be-1831afaccf00" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/c8b5c59f-0483-42ef-b3ee-4cffae6c7a52" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/532a3e60-2bac-4039-a06c-ff6bf06cb4a4" muted="false"></video>
    </td>
</tr>

</table>

### Landmark Driven

<table class="center">
    
<tr>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/1da6c46f-4532-4375-a0dc-0a4d6fd30a39" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/d4f4d5c1-e228-463a-b383-27fb90ed6172" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/18bd2c93-319e-4d1c-8255-3f02ba717475" muted="false"></video>
    </td>
</tr>

</table>

### Audio + Selected Landmark Driven

<table class="center">
    
<tr>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/4a29d735-ec1b-474d-b843-3ff0bdf85f55" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/b994c8f5-8dae-4dd8-870f-962b50dc091f" muted="false"></video>
    </td>
    <td width=30% style="border: none">
        <video controls loop src="https://github.com/antgroup/echomimic/assets/11451501/955c1d51-07b2-494d-ab93-895b9c43b896" muted="false"></video>
    </td>
</tr>

</table>

**（Some demo images above are sourced from image websites. If there is any infringement, we will immediately remove them and apologize.）**

## ⚒️ Installation

### Download the Codes

```bash
  git clone https://github.com/BadToBest/EchoMimic
  cd EchoMimic
```

### Python Environment Setup

- Tested System Environment: Centos 7.2/Ubuntu 22.04, Cuda >= 11.7
- Tested GPUs: A100(80G) / RTX4090D (24G) / V100(16G)
- Tested Python Version: 3.8 / 3.10 / 3.11

Create conda environment (Recommended):

```bash
  conda create -n echomimic python=3.8
  conda activate echomimic
```

Install packages with `pip`
```bash
  pip install -r requirements.txt
```

### Download ffmpeg-static
Download and decompress [ffmpeg-static](https://www.johnvansickle.com/ffmpeg/old-releases/ffmpeg-4.4-amd64-static.tar.xz), then
```
export FFMPEG_PATH=/path/to/ffmpeg-4.4-amd64-static
```

### Download pretrained weights

```shell
git lfs install
git clone https://huggingface.co/BadToBest/EchoMimic pretrained_weights
```

The **pretrained_weights** is organized as follows.

```
./pretrained_weights/
├── denoising_unet.pth
├── reference_unet.pth
├── motion_module.pth
├── face_locator.pth
├── sd-vae-ft-mse
│   └── ...
├── sd-image-variations-diffusers
│   └── ...
└── audio_processor
    └── whisper_tiny.pt
```

In which **denoising_unet.pth** / **reference_unet.pth** / **motion_module.pth** / **face_locator.pth** are the main checkpoints of **EchoMimic**. Other models in this hub can be also downloaded from it's original hub, thanks to their brilliant works:
- [sd-vae-ft-mse](https://huggingface.co/stabilityai/sd-vae-ft-mse)
- [sd-image-variations-diffusers](https://huggingface.co/lambdalabs/sd-image-variations-diffusers)
- [audio_processor(whisper)](https://openaipublic.azureedge.net/main/whisper/models/65147644a518d12f04e32d6f3b26facc3f8dd46e5390956a9424a650c0ce22b9/tiny.pt)

### Audio-Drived Algo Inference 
Run the python inference script:

```bash
  python -u infer_audio2vid.py
  python -u infer_audio2vid_pose.py
```

### Audio-Drived Algo Inference On Your Own Cases 

Edit the inference config file **./configs/prompts/animation.yaml**, and add your own case:

```bash
test_cases:
  "path/to/your/image":
    - "path/to/your/audio"
```

The run the python inference script:
```bash
  python -u infer_audio2vid.py
```

### Motion Alignment between Ref. Img. and Driven Vid.

(Firstly download the checkpoints with '_pose.pth' postfix from huggingface)

Edit driver_video and ref_image to your path in demo_motion_sync.py, then run
```bash
  python -u demo_motion_sync.py
```

### Audio&Pose-Drived Algo Inference
Edit ./configs/prompts/animation_pose.yaml, then run
```bash
  python -u infer_audio2vid_pose.py
```

### Pose-Drived Algo Inference
Set draw_mouse=True in line 135 of infer_audio2vid_pose.py. Edit ./configs/prompts/animation_pose.yaml, then run
```bash
  python -u infer_audio2vid_pose.py
```

### Run the Gradio UI

Thanks to the contribution from @Robin021:

```bash

python -u webgui.py --server_port=3000

```

## 📝 Release Plans

|  Status  | Milestone                                                                | ETA |
|:--------:|:-------------------------------------------------------------------------|:--:|
|    ✅    | The inference source code of the Audio-Driven algo meet everyone on GitHub   | 9th July, 2024 |
|    ✅    | Pretrained models trained on English and Mandarin Chinese to be released | 9th July, 2024 |
|    ✅    | The inference source code of the Pose-Driven algo meet everyone on GitHub   | 13th July, 2024 |
|    ✅    | Pretrained models with better pose control to be released                | 13th July, 2024 |
|    ✅    | Accelerated models to be released                                        | 17th July, 2024 |
|    🚀    | Pretrained models with better sing performance to be released            | TBD |
|    🚀    | Large-Scale and High-resolution Chinese-Based Talking Head Dataset       | TBD |

## ⚖️ Disclaimer
This project is intended for academic research, and we explicitly disclaim any responsibility for user-generated content. Users are solely liable for their actions while using the generative model. The project contributors have no legal affiliation with, nor accountability for, users' behaviors. It is imperative to use the generative model responsibly, adhering to both ethical and legal standards.

## 🙏🏻 Acknowledgements

We would like to thank the contributors to the [AnimateDiff](https://github.com/guoyww/AnimateDiff), [Moore-AnimateAnyone](https://github.com/MooreThreads/Moore-AnimateAnyone) and [MuseTalk](https://github.com/TMElyralab/MuseTalk) repositories, for their open research and exploration. 

We are also grateful to [V-Express](https://github.com/tencent-ailab/V-Express) and [hallo](https://github.com/fudan-generative-vision/hallo) for their outstanding work in the area of diffusion-based talking heads.

If we missed any open-source projects or related articles, we would like to complement the acknowledgement of this specific work immediately.

## 📒 Citation

If you find our work useful for your research, please consider citing the paper :

```
@misc{chen2024echomimic,
  title={EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditioning},
  author={Zhiyuan Chen, Jiajiong Cao, Zhiquan Chen, Yuming Li, Chenguang Ma},
  year={2024},
  eprint={2407.08136},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
```

## 🌟 Star History
[![Star History Chart](https://api.star-history.com/svg?repos=antgroup/echomimic&type=Date)](https://star-history.com/#antgroup/echomimic&Date)
