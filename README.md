
# 🤖🍳 Sassy Robot Chef: AI Recipe Generator

Welcome to **Sassy Robot Chef**, where delicious recipes come with a generous side of sass! Just input your random fridge ingredients, and our bold AI-powered chef will:
- Roast your pantry decisions 🫣
- Suggest an over-the-top, dramatic dish 🍽️
- Present a hilariously formatted recipe 📜

Built using 🤗 [Transformers](https://huggingface.co/docs/transformers/index), [OpenChat 3.5](https://huggingface.co/openchat/openchat-3.5-0106), and [Gradio](https://www.gradio.app/).

---


## 🧠 Model

We use the [OpenChat 3.5 (0106)](https://huggingface.co/openchat/openchat-3.5-0106) model — a chat-tuned large language model with a good balance of creativity and sarcasm. If performance is a concern, you can swap it with a lighter LLM like Mistral or Zephyr.

---

## 🛠️ Features

- 🤖 Roleplay prompt to make the LLM act like a cheeky chef
- 🍱 User input: ingredients (e.g., "egg, ketchup, rice")
- 📃 Output: dramatic dish name, roasted commentary, and recipe
- 🎨 Custom pink UI using Gradio + CSS
- 🌐 Public share link via Gradio

---

## 💻 How to Run

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/sassy-robot-chef.git
cd sassy-robot-chef
```

### 2. Install requirements
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
python app.py
```

Or open in **Google Colab** if you're using GPUs.

---

## 📁 Example Output

**Input**:  
`banana, ketchup, and frozen peas`

**Output**:
> "Well look at you, Picasso of poor taste. Here's your masterpiece: _'Banana Ketchup Disaster Stir Fry'_. Bon appétit (you'll need it).  
>  
> - Peel that sad banana. Regret it.  
> - Fry the peas in guilt and ketchup.  
> - Throw them together and cry.  
> - Garnish with judgment.  
>  
> You're welcome."

---

## 🧪 Technologies Used

- Python
- HuggingFace Transformers
- Gradio
- OpenChat-3.5 Model

---

## 🤝 Contributing

PRs are welcome! Want to make it sassier, add voice responses, or improve visuals? Fork away!

---

## 📜 License

MIT License

---

## 🌟 Credits

Created by [Your Name](https://github.com/yourusername)  
