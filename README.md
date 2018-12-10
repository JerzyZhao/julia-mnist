## Julia-MNIST

A mini three-layer neural network implemented by a pure Julia standard library. It's very simple, the core code is about 50 lines.

Julia provides a more complete scientific computing infrastructure at the grammatical level than Python. This micro-project is purely through the Julia standard library, without a third-party package, to build a common three-layer neural network.

Using the classic MNIST data set, the accuracy is 97.49 with a simple multi-cycle training. This result is already above the benchmark level given by [MNIST official website](http://yann.lecun.com/exdb/mnist/), but even more surprisingly, this is only implemented through Julia.


## Running

Make sure that the following tools are installed：
- Julia 1.0
- IJulia（If not, you can do so by entering `]` in REPL, and then entering the `add IJulia` installation。）


## About Data Sets

[Data Dowoload](https://drive.google.com/open?id=19MYq6yeO-qvVuEoFOrkr1Ophq4CgkRKq)

- `mnist_train_100.csv`：Consists of 100 training data；
- `mnist_test_10.csv`：Consists of 10 test data；

**The above two data can be used as the simplest test.**

- `mnist_train.csv`：Consists of 60000 training data;
- `mnist_test.csv`：Consists of 10000 test data;

The first item of each data is the correct result, followed by the 784 (28 \* 28) item is the image data.

`w6_d.jpg` and `w7_d.jpg` were hand-painted by me, and the processing became the MNIST image format. Used only as recreation.
