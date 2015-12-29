Pretty-print text to a given number of characters per column. The printing of the text is optimized by minimizing the following heuristic: For all lines other than the last line, the number of whitespace characters left at the end of the lines are all cubed and then added. For example, the following printing would receive a "penalty" of 74.

(10 characters per line), whitespace displayed as _

    The_quick_
    brown_fox_
    jumped____
    over_the__
    lazy_dog.

This optimization is done using dynamic programming.
