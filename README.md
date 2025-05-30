
# 🪄Neural Style Transfer Web App – Pixlate🦋

Transform any photograph into a masterpiece using deep learning!  
This project implements a **Neural Style Transfer Web App** built with **Streamlit**, **TensorFlow Hub**, and **Google Colab**.


---

## Project Overview

**Pixlate** is an interactive AI web app that allows users to:
- Upload a **Content Image** and a **Style Image**
- Blend them into a new, stylized artwork using a pretrained model
- Preview and **download the final output**
- Run fully in Google Colab using **Pyngrok** for real-time hosting

This app showcases the power of **neural style transfer** and democratizes creativity through AI.

---

## Tech Stack

| Component        | Description                                   |
|------------------|-----------------------------------------------|
| **Streamlit** | Interactive web UI                            |
| **TensorFlow Hub** | Pretrained Style Transfer Model       |
| **Pillow / OpenCV** | Image processing and handling        |
| **Pyngrok**   | Tunneling to access Streamlit app online      |
| **Google Colab** | Cloud execution, no setup needed         |

---

## 📂 Project Structure

```bash
neural-style-transfer-app/
├── app.py                         # Streamlit frontend logic
├── api.py                         # Style transfer function using TF Hub
├── Neural_Style_Transfer_Colab_App.ipynb  # Colab notebook for deployment
└── README.md                      # You're reading it!
```

---

## How to Run It in Google Colab

1. Open the notebook: `Neural_Style_Transfer_Colab_App.ipynb`
2. Upload all project files (`app.py`, `api.py`)
3. Execute cells step-by-step
4. Wait for **ngrok** to generate a public link
5. Click the link to open your live app

---

## ✨ Features

✅ Upload custom content and style images  
✅ Real-time stylization using pretrained model  
✅ Downloadable high-quality outputs  
✅ Minimal UI with great user experience  
✅ No local setup needed – run entirely in Colab!

---

## 📸 Demo

INPUT CONTENT IMAGE
![content](https://github.com/user-attachments/assets/5fca6fdc-6461-4a16-8b4a-5095d73836ac)

INPUT STYLE IMAGE
![style1](https://github.com/user-attachments/assets/10db9b6c-4f1a-470d-bb05-3604f8d9cac9)

STREAMLIT INTERFACE
> ![image](https://github.com/user-attachments/assets/b2859a14-2bee-4562-ac75-b392c583f0df)

OUTPUT (STYLIZED IMAGE)
![stylized_output](https://github.com/user-attachments/assets/c4e445d7-1086-4b64-a512-8a334971893b)



---

## 👩‍💻 Author

**Thilagavathi Ayyappan**  

---

## 🏷️ Tags

`Deep Learning` • `Computer Vision` • `AI Art` • `Neural Style Transfer` • `Streamlit` • `TensorFlow` • `Colab Deployment`

---

> “Art is not what you see, but what you make others see.” – Edgar Degas
