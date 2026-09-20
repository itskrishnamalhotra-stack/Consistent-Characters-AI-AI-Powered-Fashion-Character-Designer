# Consistent Character Fashion Designer

An experimental Flask and Colab workflow for generating fashion imagery while preserving a character's visual identity across outfits, poses and scenes.

> Built in 2024 as a generative-AI portfolio project.

## Capabilities

- Prompt-guided fashion image generation
- Reference-image-to-prompt workflow
- Face-consistency processing across generated images
- Body-type and visual controls through a web interface
- Generation history and downloadable results
- PDF export for selected outputs

## Architecture

```text
Reference image + prompt
          |
          v
 Image-to-prompt analysis
          |
          v
 Diffusion generation
          |
          v
 Identity-preservation stage
          |
          v
 Flask gallery and PDF export
```

## Tech stack

Python · Flask · PyTorch · Hugging Face Diffusers · CUDA · Google Colab · ReportLab

## Running the prototype

1. Open the notebook in Google Colab.
2. Enable a GPU runtime.
3. Configure a compatible image-generation checkpoint.
4. Run the cells in order and open the generated web interface.

The originally tested checkpoint is not included. Use a model whose licence permits your intended use. API keys, tokens and personal Drive paths must be supplied privately.

## Screenshots

| Generation workspace | Character results |
| --- | --- |
| ![Workspace](https://github.com/user-attachments/assets/c756361e-551d-4d11-a320-4dd1040cec0f) | ![Result](https://github.com/user-attachments/assets/5846e3fd-ceb3-4244-8faa-59087f38a74c) |
| ![Prompt controls](https://github.com/user-attachments/assets/368db6d8-d1a5-4a13-8df1-dfa7eae10819) | ![Generated character](https://github.com/user-attachments/assets/03f4d4cc-e886-468d-96c8-c5e0a4d463cb) |

<details>
<summary>View the complete screenshot gallery</summary>

![Screenshot 2](https://github.com/user-attachments/assets/490daaa3-9e62-4536-b6ac-9a01e2b972e6)
![Screenshot 3](https://github.com/user-attachments/assets/73704398-e7c7-4bf5-aaa6-3a01e2b972e6)
![Screenshot 5](https://github.com/user-attachments/assets/fcc80fae-50ed-4e35-afce-cbd72b99d048)
![Screenshot 6](https://github.com/user-attachments/assets/956d890c-d323-4cf0-868b-8e8ab9e3f415)
![Screenshot 8](https://github.com/user-attachments/assets/0ae7ffb0-98dc-450a-b939-cb0449926ca2)
![Screenshot 9](https://github.com/user-attachments/assets/8d53f405-8b25-4820-9854-a257e6f497c7)
![Screenshot 11](https://github.com/user-attachments/assets/480ad16e-eea2-4a19-b9f7-a69b6d42cb84)
![Screenshot 12](https://github.com/user-attachments/assets/ba935852-005c-4994-a763-d6282c4fa04a)
![Screenshot 13](https://github.com/user-attachments/assets/d6335404-a307-493c-a7de-d17ad893174a)

</details>

## Responsible use

Only use reference images with permission. Do not use the project for impersonation, deception or non-consensual identity manipulation.

## Status

Notebook-based portfolio prototype. A future production version should separate the UI, inference service and model configuration into reproducible packages.
