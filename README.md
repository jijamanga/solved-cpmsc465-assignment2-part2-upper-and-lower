Download Link: https://assignmentchef.com/product/solved-cpmsc465-assignment2-part2-upper-and-lower
<br>
Given a set of lines, each line is represented as `y = a * x + b`. Calculatethe number of lines in the upper-envelop and the number lines in thelower-envelop. (You may assume that there is no three lines going through thesame point. And for any three lines, they can’t be in all parallel to eachother, but it’s possible that two lines are parallel to each other.)

# Input

There are n + 1 lines, the first line gives only one number `n`, the number of lines. Each of the following lines contains two floating numbers `a` and `b` separated by space which represent a line as `y = a * x + b`.

You can assume that 0 &lt;= n &lt;= 1000, and that each floating numbersare in the range of [-100.0, 100.0].

Your code should read the input from standard input (e.g.using functions `input()/raw_input()` in Python and `cin/scanf` in C++).

# Output

Two numbers in a line separated by space, the number of lines in the upper-envelop and the number lines in the lower-envelop.

Your code should write the output to standard output (e.g. using functions `print` in Python and `cout/printf` in C++).

# Requirement

Your algorithm should run in O(nlogn) time.

Time limtation: 5 seconds.

Memory limitation: 1.0 GB.

# Environment

Your code will be running on Ubuntu 18.04.5.

Now only accept C++ and Python2/Python3 code, g++ version 7.5.0 and Python versions are Python 2.7.17 and Python 3.6.9.

# Examples and Testing

Some examples (e.g., input-x.txt and output-x.txt, x = 1, 2) are provided.A figure corresponding input-1 can be found in this repo too.For Python code, try the following to test your code“`python ./solution.py &lt; input-x.txt &gt; my-output-x.txt“`For C++ code, try the following to test your code“`g++ -o mybinary solution.cpp./mybinary &lt; input-x.txt &gt; my-output-x.txt“`

Your output `my-output-x.txt` needs to be *match exactly* to the given `output-x.txt`.On Unix-based systems you can use `diff` to compare them:“`diff my-output-x.txt output-x.txt“`On Windows you can use `fc` to compare them:“`fc my-output-x.txt output-x.txt