# Parity function

## 8-bit data set for the two-class classification problem of the *parity function*

The parity function is a generalization of the XOR function. It takes
N binary input values, coded as **x** ∈ {0, 1}<sup>N</sup> and returns 0 when having a even number of ones
in **x** and 1 when it contains an odd number of ones. More formally, f : {0, 1}<sup>N</sup> → {0, 1}, where the
solution of the discrete equation **x** · **x** = 2n + m : n ∈ ℕ, m ∈ {0, 1} decides the output of the function
f(**x**) = m.

The data set covers the 8-bit parity function, that is translated in a
data set of 256 instances obtained from the 2<sup>8</sup> possible combinations of the two values of every 8-bits
input.

The first 8 columns are the binary values of the 8-bits (features) and the last (9th and 10th) columns are the two classes of the problem (0 or 1). If you want you can reduce it to just 1-bit output (0,1) depending on your ML algorithm.

