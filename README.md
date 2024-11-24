# awesome-video-generation ( 视频生成研究资源汇总 )

本页面汇总了视频生成领域最常用、最实用的研究论文、工具和数据集。

---

## 工具与产品

| 名称            | 组织         | 特色链接                                             |
|-----------------|------------|-----------------------------------------------------|
| Sora           | OpenAI     | [官网](https://openai.com/sora)                     |
| Gen-2          | RunwayML   | [官网](https://research.runwayml.com/gen2)          |
| Animate Anyone | 阿里巴巴    | [论文](https://arxiv.org/pdf/2311.17117.pdf) [项目](https://humanaigc.github.io/animate-anyone/) |
| Stable Video   | StabilityAI| [论文](https://arxiv.org/pdf/2311.15127.pdf) [官网](https://www.stablevideo.com/) |
| VideoPoet      | Google     | [官网](https://sites.research.google/videopoet/)    |
| PixelDance     | 字节跳动    | [论文](https://arxiv.org/abs/2311.10982) [项目](https://makepixelsdance.github.io/) |

---

## 核心论文

### 文本到视频生成
- **2024年**
  - **Vlogger:** 使用文本生成短视频 [[论文]](https://arxiv.org/pdf/2401.09414.pdf) [[代码]](https://github.com/Vchitect/Vlogger)
  - **PEEKABOO:** 探索式视频生成 [[论文]](https://arxiv.org/pdf/2312.07509) [[项目]](https://jinga-lala.github.io/projects/Peekaboo/)
  - **Animate Anyone:** 控制角色动画生成 [[论文]](https://arxiv.org/pdf/2311.17117.pdf) [[代码]](https://github.com/HumanAIGC/AnimateAnyone)
  - **Stable Video Diffusion:** 高分辨率视频生成 [[论文]](https://arxiv.org/pdf/2311.15127.pdf)

### 图像到视频生成
- **2024年**
  - **VideoBooth:** 基于图像提示的视频生成 [[论文]](https://arxiv.org/pdf/2312.00777) [[项目]](https://vchitect.github.io/VideoBooth-project/)
  - **PhysGen:** 物理驱动的视频生成 [[论文]](https://arxiv.org/pdf/2409.18964) [[项目]](https://stevenlsw.github.io/physgen/)

### 视频编辑
- **2024年**
  - **Video-P2P:** 基于注意力的文本驱动视频编辑 [[论文]](https://arxiv.org/pdf/2303.04761) [[项目]](https://video-p2p.github.io/)
  - **DynVideo-E:** 结合动态场景进行视频编辑 [[论文]](https://arxiv.org/pdf/2310.10624) [[项目]](https://showlab.github.io/DynVideo-E/)
  - **DragAnything:** 物体运动控制 [[论文]](https://arxiv.org/pdf/2403.07420.pdf) [[项目]](https://weijiawu.github.io/draganything_page/)

---

## 数据集

- **UCF101:** 动作视频数据集 [[论文]](https://arxiv.org/pdf/1212.0402.pdf) [[数据集]](https://www.crcv.ucf.edu/data/UCF101.php)
- **DAVIS:** 视频目标分割数据集 [[论文]](https://arxiv.org/pdf/1704.00675.pdf) [[数据集]](https://davischallenge.org/)
- **WebVid-10M:** 视频与图像检索 [[论文]](https://arxiv.org/pdf/2104.00650.pdf) [[数据集]](https://maxbain.com/webvid-dataset/)

---

## 评估指标

- **FVD:** 评估生成视频质量 [[论文]](https://openreview.net/pdf?id=rylgEULtdN) [[代码]](https://github.com/google-research/google-research/blob/master/frechet_video_distance/frechet_video_distance.py)

---

## 常见问题
### 如何查看论文顺序？
- 论文按以下顺序组织：
  1. CVPR
  2. ICCV
  3. ECCV
  4. NeurIPS
  5. ICLR
  6. AAAI
  7. arXiv
  8. 其他
