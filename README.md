# Attention is Soft KNN

Visualizing the explicit mathematical equivalence between Transformer Attention and Nadaraya-Watson Kernel Regression.

## Live Demo

Check out the live visualization here: [https://mohitburkule.github.io/Attention_is_KNN/](https://mohitburkule.github.io/Attention_is_KNN/)

## About

This project is a single-file HTML application that visualizes how the Attention mechanism in Transformers works, by drawing parallels to Kernel Regression (KNN).

It features:
- Interactive visualization where you can drag a "Query" ring to see how it absorbs colors ("Values") from nearby "Keys".
- Real-time calculation of Attention Weights.
- Mathematical explanation and side-by-side comparison of Kernel Regression and Transformer Attention formulas.

## How to Run Locally

Simply open the `index.html` file in your web browser.

```bash
# Clone the repository
git clone <repository-url>

# Open index.html
open index.html # On macOS
xdg-open index.html # On Linux
start index.html # On Windows
```

## Technologies Used

- HTML5 Canvas
- Tailwind CSS
- MathJax (for rendering equations)
