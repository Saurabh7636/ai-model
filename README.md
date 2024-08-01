## Ollama Docker with webUI

### Requirements

* Small models (e.g., 10M parameters): 2-4 GB RAM
* Medium models (e.g., 50M parameters): 8-16 GB RAM
* Large models (e.g., 100M parameters): 16-32 GB RAM
* Extra-large models (e.g., 500M parameters): 32-64 GB RAM

### Prerequisites for LLaMA-3

According to the LLaMA documentation, LLaMA-3 has approximately 4.8 billion parameters and requires around 12 GB of memory.

**Recommended Allocation**: I'd recommend allocating at least 14-15 GB of RAM to the Docker container running LLaMA-3, providing a comfortable margin for smooth model execution.