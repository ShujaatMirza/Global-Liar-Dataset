# Global-Liar-Dataset

## Dataset Description
The Global-Liar dataset is a curated collection of statements that are regionally, label-, and cut-off-date balanced. This dataset comprises both true and false statements, all published before and after the OpenAI training cut-off date for models in September 2021. It is crafted to circumvent potential biases from datasets possibly used in model fine-tuning and to address the prevalent Western-centric focus of existing datasets.

### Key Features
- **Balance**: Ensures equal representation of six global regions: Africa, Asia-Pacific, Europe, Latin America, North America, and the Middle East.
- **Diversity**: Contains 100 statements from each region, amounting to a broad spectrum of perspectives.
- **Temporal Relevance**: Includes statements from periods before and after the widely recognized AI training cut-off, enhancing its relevance for current models.
- **Evaluation**: Designed for a nuanced and comprehensive evaluation of fact-checking performance of AI models, particularly those beyond Western datasets.

The dataset’s structure allows for comprehensive assessments across different dimensions, such as regional veracity and temporal relevance, offering a unique resource for advancing fact-checking AI research.

### Contents
- `data/`: This directory contains the dataset files.
-- The dataset file "600_statements.tsv" contains 600 statements, balanced across regions/misinformation labels/time.
- `scripts/`: This directory contains scripts for processing or analyzing the dataset.
-- The Python notebook "demo_load_dataset.ipynb" contains a demo for loading the dataset.


## Contribution
Contributions to the Global-Liar dataset are welcome. To contribute, please follow the guidelines in the `CONTRIBUTING.md` file.

## License
This dataset is released under the [License Name]. For more information, see the `LICENSE` file in this repository.

## Citation
If you use the Global-Liar dataset in your research, please use the following citation:

```bibtex
@misc{global_liar_2023,
  title={Trustworthiness of LLMs in Fact-Checking: Stability \& Factuality of GPT Models over Time and Geographic Regions},
  author={[Shujaat Mirza, Bruno Coelho, Yuyuan Cui, Christina Poepper, Damon McCoy]},
  year={2023},
  publisher={arXiv}
}
```


## Contact

For questions and feedback, please open an issue in the GitHub repository or contact us directly at ...



