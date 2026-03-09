# Image-processing
CUDA Image Processing Project

Student Name: Mitran R

 Project Overview

This project implements GPU-accelerated image processing using CUDA. The application processes large grayscale images using CUDA kernels and CUDA streams. The goal is to demonstrate parallel image processing and performance comparison between CPU and GPU.

Implementation Details

• Implemented CUDA kernel for image processing.

• Used CUDA streams for asynchronous execution.

• Measured CPU time, GPU time, and stream execution time.

• Processed 200 images on GPU

Performance Results

CPU Time: 0.0274350643157959 GPU Time: 0.0040264129638671875 Speedup GPU vs CPU: 6.813773093320701 Processed 500 images on GPU Total GPU Time: 0.21869349479675293 seconds

Screenshots

GPU vs CPU Time

<img width="558" height="81" alt="Screenshot 2026-03-09 175946" src="https://github.com/user-attachments/assets/fff11887-bd20-4ead-9420-4670ddd5e589" />

GPU Time

<img width="534" height="57" alt="Screenshot 2026-03-09 175956" src="https://github.com/user-attachments/assets/877ba47b-5866-4522-992a-91e4aa5a74dd" />

processed_images.png

<img width="832" height="551" alt="image" src="https://github.com/user-attachments/assets/7852b4ef-a189-4ae8-bc03-8f83868d8570" />
