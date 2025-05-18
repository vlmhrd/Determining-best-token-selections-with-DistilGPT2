# Determining-best-token-selections-with-DistilGPT2

# Goal
The goal of this project is to experiment with different token selection strategies using the DistilGPT2 language model and to track the carbon emissions produced during text generation. By analyzing various decoding techniques, the notebook seeks to assess both the qualitative output and the environmental impact of running these models.

# Description
This Jupyter Notebook explores and compares several token selection strategies for text generation with DistilGPT2, including:

- N-gram penalty decoding
- Beam search
- Sampling with temperature and top-k filtering
  
Each method is implemented and demonstrated with example prompts. In addition to generating text, the notebook integrates the CodeCarbon library to monitor and log the energy consumption and estimated CO₂ emissions for each generation run. Emissions data is saved and displayed for further analysis, providing insight into the environmental footprint of different decoding strategies.

# Tools
- Transformers (Hugging Face): For the DistilGPT2 model and tokenization.
- CodeCarbon: To track energy usage and estimate carbon emissions.
- Pandas: For loading and analyzing emissions logs.
- Python 3.12: Primary programming language used in the notebook.
