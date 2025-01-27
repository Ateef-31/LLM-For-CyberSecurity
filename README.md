# Cybersecurity LLM

## Overview
This project involves training and deploying a cybersecurity-focused Large Language Model (LLM) using `unsloth`, `transformers`, and other libraries. The model is fine-tuned on a penetration testing dataset and allows users to ask cybersecurity-related questions.

---

## Requirements
To run this project, ensure the following libraries are installed:

- **unsloth**
- **xformers**
- **transformers**
- **datasets**
- **trl**
- **torch**
- **accelerate**
- **bitsandbytes**

You can install all dependencies using:
```bash
pip install unsloth "xformers==0.0.28.post2" transformers datasets trl torch accelerate bitsandbytes
```

---

## Files in the Project
1. **main.py**: Contains the `SecurityModelManager` class and the main function to interact with the LLM.
2. **requirements.txt**: (Optional) A file to list the required libraries for easy installation.

---

## How to Run the Project
1. Install all the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```
2. Run the `main.py` script.
   ```bash
   python main.py
   ```
3. Follow the prompts to ask your cybersecurity-related questions.

---

## Usage Example
- Start the script:
  ```bash
  python main.py
  ```
- Input a question:
  ```
  Enter your cybersecurity question (or 'quit' to exit): What is penetration testing?
  ```
- The model will generate an answer in real time.

---

## Notes
- The dataset used for fine-tuning is `Isamu136/penetration_testing_scraped_dataset`.
- The model is optimized for inference with 4-bit quantization using `bitsandbytes`.
- Ensure you have access to a CUDA-enabled GPU for optimal performance.

---

## Disclaimer
This project is intended for educational purposes and to assist in learning about cybersecurity concepts. It is not designed for production-level applications.

---
