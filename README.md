# prjctr-18-algorithms-and-data-structures

Implement class for Balanced Binary Search Tree that can insert, find and delete elements.

Generate 100 random datasets and measure complexity.

Implement Counting Sort algorithm.

Figure out when Counting Sort doesn’t perform.

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pytest tests/test_red_black_tree.py -v -s
pytest tests/test_red_black_tree_performance.py -v -s
pytest tests/test_counting_sort.py -v -s
pytest tests/test_counting_sort_performance.py -v -s
```

![red-black-tree performance](rbt_performance.png)

### Figure out when Counting Sort doesn’t perform

Counting sort is memory-inefficient when difference between min and max value (K) is much larger than number of elements (N)

![red-black-tree performance](counting_sort_performance.png)
