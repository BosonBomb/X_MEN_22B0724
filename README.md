Sure! Here's the simplified `README.md` with just the summary part:

---

# Anime Video Transformation with AnimeGANv3 and Face Segmentation

This project is a pipeline for converting normal videos into anime-styled videos using a combination of **AnimeGANv3** and **face segmentation** techniques. The solution applies specialized transformations to human faces and non-human areas in each frame to produce a visually consistent anime-style video.

---

## Features

- **AnimeGANv3 Integration**: Utilizes the pre-trained AnimeGANv3 model for stylizing non-human regions of the video.
- **Face-Specific Transformation**: Employs a face segmentation model to apply detailed anime-style painting to human regions using `face2paint` from AnimeGAN2.
- **Customizable Workflow**: Modular functions for segmentation, transformation, and video processing.
- **GPU Acceleration**: Optimized for CUDA when available for faster processing.
- **ONNX Runtime**: Uses ONNX format for efficient inference with AnimeGANv3.

---

## How It Works

1. **Segmentation**: Each video frame is segmented into human and non-human regions using a pre-trained segmentation model.
2. **Face Painting**: The `face2paint` model applies anime-style painting to human faces.
3. **Non-Human Stylization**: The AnimeGANv3 ONNX model processes non-human areas to transform them into an anime style.
4. **Combination**: The transformed face and non-face regions are combined seamlessly into a single frame.
5. **Video Output**: All frames are recombined into an anime-styled video.

---

Let me know if you need further adjustments!
