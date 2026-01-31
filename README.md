🤖 Problem It Solves

Cloud-based LLMs are costly and raise privacy concerns.
This project demonstrates running a large language model locally, enabling offline and private inference without relying on cloud APIs.

🛠 Tech Stack

Python

Mistral-7B

Hugging Face

ctransformers

CPU-based inference

🏗 Architecture
User Prompt
     |
Tokenizer
     |
Local Mistral-7B Model
     |
Generated Response

▶ How to Run
git clone https://github.com/Shabbirh10/on-device-llm.git
cd on-device-llm
pip install -r requirements.txt
python run_model.py

✨ Highlights

Fully offline LLM execution

Optimized for low-resource systems

Practical understanding of LLM deployment constraints
