
# Model Hubs and Beyond: Analyzing Model Popularity, Performance, and Documentation

## Links

* Paper: [arXiv:2503.15222](https://arxiv.org/abs/2503.15222)
* Dataset: [Hugging Face](https://huggingface.co/datasets/LingoIITGN/reddit-sentiment-model-hubs)

## Hugging Face usage

```python
from datasets import load_dataset

# Login using e.g. `huggingface-cli login` to access this dataset
ds = load_dataset("LingoIITGN/reddit-sentiment-model-hubs", "human_annotated")
```

```python
from datasets import load_dataset

# Login using e.g. `huggingface-cli login` to access this dataset
ds = load_dataset("LingoIITGN/reddit-sentiment-model-hubs", "raw_reddit")
```



## Citing

```bibtex
@misc{kadasi2025modelhubsbeyondanalyzing,
      title={Model Hubs and Beyond: Analyzing Model Popularity, Performance, and Documentation}, 
      author={Pritam Kadasi and Sriman Reddy and Srivathsa Vamsi Chaturvedula and Rudranshu Sen and Agnish Saha and Soumavo Sikdar and Sayani Sarkar and Suhani Mittal and Rohit Jindal and Mayank Singh},
      year={2025},
      eprint={2503.15222},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2503.15222}, 
}
```
