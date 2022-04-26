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

## Baseline Model
We used [numnetplus](https://github.com/llamazing/numnet_plus) as the baseline model in NumGLUE. We use reading comprehension as the common format and convert questions of all tasks to the reading comprehension format. 

For more details, please refer to our paper [NumGLUE: A Suite of Fundamental yet Challenging Mathematical Reasoning Tasks](https://arxiv.org/abs/2204.05660)

Feel free to cite us

```bibtex
@article{mishra2022numglue,
  title={NumGLUE: A Suite of Fundamental yet Challenging Mathematical Reasoning Tasks},
  author={Mishra, Swaroop and Mitra, Arindam and Varshney, Neeraj and Sachdeva, Bhavdeep and Clark, Peter and Baral, Chitta and Kalyan, Ashwin},
  journal={ACL},
  year={2022}
}
```
If you use the NumGLUE data, please cite the source dataset papers.
The full bibtex of source dataset papers is [here](doc/source_citation.md). 
