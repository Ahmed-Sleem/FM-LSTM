# Fractal Memory LSTM (FM-LSTM)

**Paper:** *Fractal Memory LSTM: A Hierarchical Multi-Resolution Approach*  
 

---

## Overview
FM-LSTM is a PyTorch implementation of a **hierarchical recurrent architecture** inspired by fractal memory.  
It splits LSTM cell memory into multiple levels, enabling **multi-scale temporal learning** with fewer parameters.  

- Parameter-efficient (40–50% fewer params than LSTM in our tests)  
- Designed for **long-term temporal dependencies**  
- Tested on Weather, Air Quality, Sleep, and SST datasets  

👉 See the **[paper](link-to-paper)** for full theory, experiments, and analysis.

---

```bibtex
@article{sleem2025fmlstm,
  title={Fractal Memory LSTM: A Hierarchical Multi-Resolution Approach to Long-Term Temporal Dependencies},
  author={Ahmed Sleem},
  year={2025},
  note={Preprint / code: https://github.com/Ahmed-Sleem/FM-LSTM}
}
```

