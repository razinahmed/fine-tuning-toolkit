# Fine-Tuning Toolkit

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![ML](https://img.shields.io/badge/ML-Fine_Tuning-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A toolkit for fine-tuning large language models on custom datasets. Provides streamlined workflows for data preparation, training configuration, model fine-tuning, and evaluation across popular LLM architectures.

---

## Features

- **Data Preparation** -- Convert raw data into fine-tuning-ready JSONL format
- **Multi-Model Support** -- Fine-tune GPT, LLaMA, Mistral, and other LLM architectures
- **Hyperparameter Management** -- Configurable learning rates, epochs, batch sizes, and LoRA parameters
- **Training Monitoring** -- Real-time loss tracking and validation metrics
- **Checkpoint Management** -- Save, resume, and compare training checkpoints
- **Evaluation Pipeline** -- Automated benchmarking of fine-tuned models against base models

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Core runtime |
| Transformers / PEFT | Model fine-tuning |
| PyTorch | Training framework |
| CSS3 | Dashboard theming |
| Makefile | Build and test automation |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/fine-tuning-toolkit.git
cd fine-tuning-toolkit

# Install dependencies
pip install -r requirements.txt

# Prepare training data
python prepare.py --input data.csv --output train.jsonl

# Start fine-tuning
python train.py --model base_model --data train.jsonl --epochs 3
```

---

## Project Structure

```
fine-tuning-toolkit/
├── styles/
│   └── theme.css           # Dashboard theme configuration
├── Makefile                # Build and test commands
├── LICENSE                 # MIT License
├── SECURITY.md             # Security policy
└── README.md
```

---

## Usage

```bash
# Build the project
make build

# Run tests
make test
```

---

## Contributing

1. Fork the repository
2. Create a feature branch -- `git checkout -b feature/your-feature`
3. Commit your changes -- `git commit -m "feat: add new feature"`
4. Push and open a Pull Request

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Built by [Razin Ahmed](https://github.com/razinahmed)**
