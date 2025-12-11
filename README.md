# cupid-starfield
💘 cupid arrow starfield with hand gesture
💘 Cupid's Starfield | 丘比特的星空

🌟 Concept | 项目理念

This project is an interactive 3D generative art installation combining advanced visualization (Three.js), real-time human-computer interaction (MediaPipe Gesture Recognition), and emotional computing (Gemini LLM). It transforms the user's sentiment into a dynamic visual and auditory experience, demonstrating the powerful integration of AI and generative art in educational and creative contexts.

本项目是一个交互式的 3D 生成艺术装置，融合了先进的可视化技术 (Three.js)、实时人机交互 (MediaPipe 手势识别) 和情感计算 (Gemini 大语言模型)。它将用户的情感转化为动态的视觉和听觉体验，展示了人工智能与生成艺术在教育和创意领域深度融合的巨大潜力。

✨ Features | 核心功能

Feature

English Description

中文描述

Generative Poetics

Uses the Gemini API to write a unique, cosmic-themed love poem based on the user's input name.

使用 Gemini API 根据用户输入的名字，即时创作一首包含宇宙意象的专属情诗。

TTS Aural Experience

The generated poem is instantly rendered via Text-to-Speech (TTS) and read aloud in an ethereal voice, enhancing the immersion.

通过 TTS 语音合成，将生成的情诗以空灵的声音朗读出来，带来沉浸式听觉体验。

Gesture-Controlled Morphing

Utilizes the webcam and MediaPipe to detect hand gestures in real-time.

利用摄像头和 MediaPipe 实时检测手部姿态。

Dynamic 3D Morph

Open Hand (✋): Particles disperse into a chaotic, micro-motion starfield. Closed Fist (✊): Particles instantly morph into a "Cupid's Arrow Piercing a Heart" shape, with the input name rendered in 3D beneath the heart.

张开手掌 (✋): 粒子散开成动态、微动的星空。握紧拳头 (✊): 粒子立即汇聚成“丘比特一箭穿心”的形态，心上人的名字以 3D 形式悬浮在爱心下方。

Micro-Motion Starfield

Adds subtle sine-wave based oscillation to all particles, ensuring the starfield remains dynamic and alive even in its resting state.

为所有粒子添加了基于正弦波的微小振动，确保星空在静态时也保持动态和生命力。

🚀 Technology Stack | 技术栈

3D Visualization: Three.js (WebGL)

Generative AI & TTS: Gemini API (gemini-2.5-flash-preview-09-2025 for text, gemini-2.5-flash-preview-tts for voice)

Real-time Interaction: MediaPipe Hands (for computer vision and gesture tracking)

Web Standard: HTML, JavaScript, CSS (Single-file application)

💡 How to Use | 使用指南

Access Camera: The application will request access to your webcam for gesture recognition.

Input Name: Type the name of your beloved into the input field.

Generate AI Content: Click the "✨ 聆听星语" button to trigger the Gemini API, generating the poem and starting the TTS audio.

Interact with Gestures:

Show an Open Hand (✋) to the camera: The particles will scatter into a chaotic starfield.

Show a Closed Fist (✊) to the camera: The particles will converge, forming the heart shape and displaying the name.

Created by Professor Fei Xiang.
