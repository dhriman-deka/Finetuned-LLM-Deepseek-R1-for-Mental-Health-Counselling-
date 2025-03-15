

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Google%20Colab-orange)

## 📋 Overview

This project provides a Google Colab notebook for fine-tuning the DeepSeek R1 Distill Llama 8B model to create a mental health counseling assistant. The notebook delivers an end-to-end solution: from setting up the environment to loading the model, preparing data, training, testing, and saving results.

> ⚠️ **Important**: This AI assistant is not a replacement for professional mental health services. It is intended as a supplementary tool and should be used responsibly.

## ✨ Key Features

- **All-in-one Colab Notebook**: Complete pipeline from setup to inference
- **Mental Health Focus**: Specialized for supportive counseling responses
- **Efficient Fine-tuning**: Uses Unsloth for 2x faster training and 70% less memory
- **Accessible**: Runs on free Colab GPU resources
- **Ethical Design**: Includes responsible use guidelines

## 🚀 Getting Started

1. **Open the Notebook**:
   - Open `Mental_Health_Counselor_Training.ipynb` in Google Colab
   - Or click [![Open In Colab](https://colab.research.google.com/gist/dhriman-deka/a8a51382a5c88e300cd1460285e11732/copy-of-_mental_health_counseling_ai_assistant_fine_tuning_deepseek_r1_8b.ipynb)

2. **Run the Notebook**:
   - The notebook includes all necessary dependencies installation
   - Simply run each cell in sequence

3. **Save Your Model**:
   - The notebook includes code to save your fine-tuned model
   - You can download it locally or save to Hugging Face Hub

## 📊 Notebook Contents

The notebook provides a complete workflow:

1. **Environment Setup**: Installing Unsloth and dependencies
2. **Model Loading**: Setting up DeepSeek R1 Distill Llama 8B with 4-bit quantization
3. **Data Preparation**: Processing mental health counseling conversations
4. **Model Fine-tuning**: Training with optimized parameters
5. **Testing**: Evaluating the model on diverse counseling scenarios
6. **Model Saving**: Exporting the fine-tuned model
7. **Usage Guidelines**: Ethical considerations and responsible use

## 🧠 Technical Details

- **Base Model**: DeepSeek R1 Distill Llama 8B from Unsloth
- **Dataset**: 3,500+ professional counseling conversations 
- **Fine-tuning Method**: Parameter-efficient LoRA (r=16, alpha=16)
- **Training Parameters**: 
  - Learning rate: 1e-4 with cosine scheduler
  - 300 steps with gradient accumulation
  - Specialized counseling prompt template

## 🛡️ Ethical Guidelines

This project emphasizes responsible use:

- The AI assistant is not a replacement for professional mental health services
- Always disclose when responses are AI-generated
- For crisis situations, refer to professional services:
  - National Suicide Prevention Lifeline: 988 or 1-800-273-8255
  - Crisis Text Line: Text HOME to 741741

## ⚠️ Limitations

- The model may provide generic responses to complex situations
- Cannot diagnose medical conditions
- Limited context window (2048 tokens)
- Performance depends on GPU available in Colab

## 🙏 Acknowledgments

- DeepSeek AI for the distilled Llama model
- Unsloth for optimization libraries
- Mental health professionals who contributed to the dataset
- The open-source AI community

---

For questions or to report issues, please use the GitHub issues tab for this repository.
