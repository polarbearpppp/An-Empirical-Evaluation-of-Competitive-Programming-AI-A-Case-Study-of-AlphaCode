#  An-Empirical-Evaluation-of-Competitive-Programming-AI-A-Case-Study-of-AlphaCode

This is the experiment and dataset for the research.

## 1). Start with the collection dataset.
using ```Collecting_HumanCode.ipynb``` .
We then filtered only the problem that both passed in Python and C++ in AlphaCode.

## 2). Codehash Method (https://github.com/NAIST-SE/CodeHash).
we applied the following method to our research to create 2 shell scripts.

In the target directory.

First ```tokenizer.sh``` to tokenize our data to token. We then find the uniqueness between AlphaCode and human code as ``` find_uniqueness.ipynb```

Second ``` similar.sh```
to find similarities between code solution Alphacode and Humancode submission and we also illustrate the result using a boxplot as ```boxplot.ipynb```

## 3). Coding a code that generate input for test performance Human code and Alpha code.

code is in ```benchmark_test_perf``` directory.

## 4). Test performance in term of execution time and memory usage and statistical t-test independent.

using ```pythonPerformance.sh ``` in bash_execute_mprof directory to test Python Performance.
using ```cppPerformanceO2.sh``` in bash_execute_mprof directory to test C++ performance.
after that we stistical test as ```indepenentTtest.ipynb```



## License
[MIT](https://choosealicense.com/licenses/mit/)
