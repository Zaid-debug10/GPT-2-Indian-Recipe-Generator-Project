A GPT-2-based generative AI model that creates Indian recipes from prompts like "To make Masala Karela." Built with Python, Hugging Face Transformers, and Weights & Biases for experiment tracking. Evaluated with BLEU (0.0143) and ROUGE scores.

## 📖 Overview
- **Objective:** Generate Indian recipes using generative AI.
- **Dataset:** IndianFoodDataset.csv (1,185 recipes).
- **Model:** GPT-2, fine-tuned for 3 epochs.
- **Evaluation:** BLEU (0.0143 avg), ROUGE scores (e.g., ROUGE-1 F1: 0.176 for Masala Karela).
- **Tools:** Python, Hugging Face Transformers, Weights & Biases, NLTK, Gradio, Google Colab.

## 📊 Results
| Prompt                          | BLEU Score | ROUGE-1 F1 |
|---------------------------------|------------|------------|
| To make Masala Karela          | 0.0035     | 0.176      |
| Tomato Puliogere is prepared by| 0.0023     | 0.115      |
| Ragi Vermicelli Recipe starts with | 0.0068 | 0.146      |
| Gongura Chicken Curry Recipe   | 0.0393     | 0.211      |
| Andhra Style Alam Pachadi is made by | 0.0194 | 0.215    |

![BLEU/ROUGE Scores](screenshots/bleu_rouge_scores.png)

## 🛠️ Setup
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/gpt2-indian-recipe-generator.git
   cd gpt2-indian-recipe-generator
