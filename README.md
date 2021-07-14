# Daily Coding Problem: Problem #5 [Medium]

`cons(a, b)` constructs a pair, and `car(pair)` and `cdr(pair)` returns the first and last element of that pair. 

For example, `car(cons(3, 4))` returns `3`, and `cdr(cons(3, 4))` returns `4`.

Given this implementation of cons:

<pre>
def cons(a, b):
    def pair(f):
        return f(a, b)
    return pair
</pre>

Implement `car` and `cdr`.

# Technologies

* Python 3.8

# Preview

![](https://github.com/mglacayo07/DailyCodingProblem5/blob/main/preview.png)
