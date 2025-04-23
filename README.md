# 💬 MotivaBot: Your Personal Motivation Coach

MotivaBot is a fine-tuned language model designed to provide motivational quotes based on users’ emotional inputs. Whether someone feels stuck, overwhelmed, or unsure, MotivaBot replies with an encouraging, supportive quote — just like a virtual cheerleader.

Built on top of [google/flan-t5-small](https://huggingface.co/google/flan-t5-small), this project demonstrates how a general-purpose, instruction-tuned Large Language Model (LLM) can be fine-tuned on a small, custom dataset to perform a highly specific and empathetic task: motivational quote generation.

---

## 🧠 What It Does

- Takes user input such as: `"I feel like giving up"` or `"I'm exhausted"`
- Processes it with a fine-tuned `Flan-T5` model
- Outputs a personalized motivational quote such as:
  - _“You are stronger than you think.”_
  - _“Keep going. Everything you need will come to you at the right time.”_

---

## 🎯 Project Highlights

- **Model:** Fine-tuned version of `google/flan-t5-small`
- **Dataset:** 250 curated emotion–quote pairs created manually
- **Training:** Hugging Face `Trainer` API, 5 epochs, learning rate of 3e-4
- **UI:** Deployed as a web app using Gradio for real-time interaction
- **Deployment:** One-click chatbot with a public shareable link

---

## 🛠️ Key Technologies

- `transformers` (Hugging Face)
- `datasets` for preprocessing and splitting
- `gradio` for user interaction
- `torch` and `accelerate` for training
- `bitsandbytes` and `peft` for efficient memory usage

---

## 📊 Why This Matters

MotivaBot isn’t just a chatbot — it’s an experiment in emotional AI. It shows how LLMs can be customized not just for technical tasks, but also for **human-centered design** that helps people feel heard, seen, and uplifted.

This project is especially relevant in an era where AI tools are increasingly part of everyday emotional and mental wellness experiences.

---

## 🚀 Use Cases

- Daily motivational boosters
- Support tool for students and professionals
- Companion feature in wellness or mental health apps
- Demo for fine-tuning LLMs on small, meaningful datasets

---

## 🧾 Licensing & Acknowledgements

- Based on models from [Hugging Face](https://huggingface.co/)
- Inspired by emotional wellness apps and daily quote tools
- Created for INFO 7375 – Branding & AI @ Northeastern University

---

## 🙋‍♀️ Created By

**Sreeja** — AI enthusiast, builder, and branding strategist.

Feel free to fork this repo or use the dataset and model structure for your own motivational or emotional intelligence projects 💖
"""

