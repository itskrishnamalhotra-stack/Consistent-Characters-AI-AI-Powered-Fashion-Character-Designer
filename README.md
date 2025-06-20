you should change the stable-diffusion-v1-5/stable-diffusion-v1-5 model with a better one as i used a difrent model

Description
Developed an end-to-end pipeline and interactive web UI for generating photo-realistic, fashion-style character images with consistent face identity across multiple poses. The app supports:

Prompt-driven Image Generation
• Built on Hugging Face Diffusers + PyTorch, leveraging the RealVisXL V4.0 model for high-fidelity outputs
• Custom “image-to-prompt” module to reverse-engineer prompts from existing reference images

Face Consistency Engine
• Integrated Roop for face preservation and swapping to ensure the same character identity across different outfits/angles

Flask Web Application
• Interactive UI with user-uploadable face images, text prompt input, and body-type presets
• Infinite-scroll gallery showing generation history and downloadable assets
• On-the-fly PDF report generation (via ReportLab) for batch outputs

Seamless Deployment in Colab
• Automated environment setup and ngrok tunneling for instant access
• Dependency management scripts for CUDA-optimized PyTorch and Hugging Face libraries

My Contributions

Architected the end-to-end data and model pipeline in Python

Developed the Flask + ngrok web interface for real-time image generation

Implemented the image-to-prompt converter using Stable Diffusion embeddings

Optimized face-swap integration to run at interactive speeds

Packaged outputs into downloadable PDFs with custom formatting

Technologies & Tools
Python • Flask • PyTorch • Hugging Face Diffusers • Roop • Pyngrok • ReportLab • CUDA • Colab

![1](https://github.com/user-attachments/assets/c756361e-551d-4d11-a320-4dd1040cec0f)
![2](https://github.com/user-attachments/assets/1c3978f5-f32b-4b50-a6e3-d1f49537f228)
![3](https://github.com/user-attachments/assets/5e0d1594-3955-4cb7-824e-d1b24ffca630)
![4](https://github.com/user-attachments/assets/5846e3fd-ceb3-4244-8faa-59087f38a74c)
![5](https://github.com/user-attachments/assets/fcc80fae-50ed-4e35-afce-cbd72b99d048)
![6](https://github.com/user-attachments/assets/956d890c-d323-4cf0-868b-8e8ab9e3f415)
![7](https://github.com/user-attachments/assets/368db6d8-d1a5-4a13-8df1-dfa7eae10819)
![8](https://github.com/user-attachments/assets/0ae7ffb0-98dc-450a-b939-cb0449926ca2)
![9](https://github.com/user-attachments/assets/8d53f405-8b25-4820-9854-a257e6f497c7)
![10](https://github.com/user-attachments/assets/03f4d4cc-e886-468d-96c8-c5e0a4d463cb)
![11](https://github.com/user-attachments/assets/480ad16e-eea2-4a19-b9f7-a69b6d42cb84)
![12](https://github.com/user-attachments/assets/ba935852-005c-4994-a763-d6282c4fa04a)
![13](https://github.com/user-attachments/assets/d6335404-a307-493c-a7de-d17ad893174a)









