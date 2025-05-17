# 🧠 AI Image Generator Web App

A responsive and interactive web application that uses Hugging Face's API to generate high-quality images from natural language prompts using advanced AI models like Stable Diffusion and FLUX.

---

## 🚀 Features

- ✍️ Prompt-based image generation
- 🎲 Random prompt generator with typing animation
- 🧠 Model selection (e.g., Stable Diffusion XL, FLUX.1)
- 🖼️ Aspect ratio and image count customization
- 🌙 Light/Dark theme toggle with localStorage support
- 🖼️ Dynamic gallery display with loading animations
- 📥 One-click image download
- ❌ Error handling and status feedback

---

## 🔧 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **API:** Hugging Face Inference API
- **UI Tools:** Font Awesome, Google Fonts
- **Models Used:** Stable Diffusion, FLUX.1-dev, FLUX.1-schnell

---

## 🧠 How It Works

1. User enters a prompt or generates a random one.
2. Selects model, image count (1–4), and aspect ratio.
3. Submits form to call the Hugging Face API.
4. The API responds with AI-generated images which are rendered on the page.
5. Users can view and download the generated images.
