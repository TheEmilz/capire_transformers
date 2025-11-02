# 🤖 Interactive Tutorial: Transformer Architecture

An interactive and visual tutorial to understand the Transformer architecture, introduced in the paper "Attention is All You Need" (2017).

## 📋 Description

This project offers a fully interactive tutorial that allows you to visually explore how the Transformer architecture works, the foundation of modern models like GPT, BERT, and many others.

## ✨ Features

- **Interactive Visualization**: Click on each component to explore detailed explanations
- **Animations**: Watch data flow through the encoder and decoder
- **Translation Demo**: See how Transformers translate from one language to another
- **Q, K, V Visualization**: Explore Query, Key, and Value matrices in detail
- **RNN vs Transformer Comparison**: Understand the advantages of Transformers over RNNs
- **Attention Playground**: Experiment with attention mechanisms in real-time
- **Multi-Head Detail**: Visualize how each attention head captures different patterns
- **3D Positional Encoding**: Interactive visualization of positional encoding
- **Training Simulation**: Observe the training process with loss curves
- **Complexity Calculator**: Calculate FLOPs, memory, and time for your model
- **Interactive Quiz**: Test your understanding of concepts
- **Code View**: View implementations in PyTorch, TensorFlow, and pseudo-code
- **Debug Mode**: Inspect tensors step-by-step through the network

## 🚀 How to Run the Project Locally

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required! It's all vanilla HTML, CSS, and JavaScript

### Method 1: Direct Opening (Easiest)

1. **Download the repository**:
   ```bash
   git clone https://github.com/TheEmilz/capire_transformers.git
   cd capire_transformers
   ```

2. **Open the HTML file**:
   - Double-click on `v6.html`
   - Or drag it into your browser
   - Or right-click → "Open with" → Select your browser

3. **Start exploring!** 🎉

### Method 2: Local HTTP Server (Recommended)

While not strictly necessary, using a local HTTP server can ensure optimal functionality:

**With Python 3**:
```bash
cd capire_transformers
python3 -m http.server 8000
```

**With Python 2**:
```bash
cd capire_transformers
python -m SimpleHTTPServer 8000
```

**With Node.js (using npx)**:
```bash
cd capire_transformers
npx http-server -p 8000
```

**With PHP**:
```bash
cd capire_transformers
php -S localhost:8000
```

Then open your browser and visit: `http://localhost:8000/v6.html`

## 🎮 How to Use the Tutorial

1. **Explore Components**: Click on each block (Input, Embedding, Attention, etc.) to see detailed explanations
2. **Animate Flow**: Use the "▶️ Animate Data Flow" button to see how data moves through the network
3. **Interactive Demos**: Try all available demos:
   - 🌍 Translation Demo
   - 🔍 Visualize Q, K, V
   - 🔄 RNN vs Transformer
   - 🎮 Attention Playground
   - 🎯 Multi-Head Detail
   - 📊 3D Positional Encoding
   - 📈 Training Visualization
   - 🧮 Complexity Calculator
   - 🎓 Quiz
   - 💻 Code View
   - 🐛 Debug Mode
4. **Learn with Quiz**: Test your understanding with interactive questions

## 🌐 Browser Compatibility

The tutorial works on all modern browsers:

- ✅ Google Chrome (version 90+)
- ✅ Mozilla Firefox (version 88+)
- ✅ Safari (version 14+)
- ✅ Microsoft Edge (version 90+)
- ✅ Opera (version 76+)

## 📱 Responsive Design

The tutorial is optimized for:
- 💻 Desktop
- 📱 Tablet
- 📱 Smartphone (some visualizations are adapted for small screens)

## 🎯 What You'll Learn

- How the **Self-Attention** mechanism works
- The complete **Transformer** architecture (Encoder and Decoder)
- The concept of **Multi-Head Attention**
- How **Positional Encoding** works
- The differences between **Transformers and RNNs**
- The **computational complexity** of the architecture
- How Transformers are used in **translation**, **text generation**, and more

## 🔧 Technologies Used

- **HTML5**: Page structure
- **CSS3**: Styling and animations (gradients, transitions, animations)
- **Vanilla JavaScript**: All interactive logic and visualizations
- **Canvas API**: For 3D visualizations and charts

## 📚 Additional Resources

- [Original Paper: "Attention is All You Need"](https://arxiv.org/abs/1706.03762)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [Transformer Architecture - PyTorch Documentation](https://pytorch.org/docs/stable/generated/torch.nn.Transformer.html)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more details.

## 👨‍💻 Author

**TheEmilz**

---

⭐ If you find this project useful, leave a star on GitHub!
