# NumGLUE
NumGLUE is a multi-task benchmark that evaluates the performance of AI systems on eight different tasks, that at their core require simple arithmetic understanding.

## Dataset
NumGLUE has 8 tasks
- Task 1: Commonsense + Arithmetic Reasoning
- Task 2: Domain Specific + Arithmetic Reasoning
- Task 3: Commonsense + Quantitative Comparison
- Task 4: Fill-in-the-blanks Format
- Task 5: Reading Comprehension (RC) + Explicit Numerical Reasoning
- Task 6: Reading Comprehension (RC) + Implicit Numerical Reasoning
- Task 7: Quantitative NLI
- Task 8: Arithmetic Word Problems

Download data from `./data/.` It contains the train, dev and test split. Note that the provided task types need to be only used for evaluating model performance across various tasks. They should not be used as additional information during model training, since one of the goal in this benchmark is to identify task types directly from data.

Feel free to cite us

```bibtex
@article{,
  title={},
  author={},
  journal={},
  year={}
}
```
If you use the NumGLUE data, please cite the source dataset papers.
The full bibtex of source dataset papers is [here](doc/source_citation.md). 
