# Matrix Transformation 

The task is to transform matrix in the files of this document which lack the correct formatting for matrices 
which has a vertical line to **separate** the coefficients from the solution. 

For each of the files you will delegage a **sub-agent**.

--- 

## Task 

The only task is what I mentioned you before. You will transform them by using 

```tex 
\left[
\begin{array}

\end{array}
\right]
```
and of course keeping the coefficients. 

**Example**: 

From 

```tex 
\[
    \begin{bmatrix}
        2  & 3 & 1  & | & 1 \\
        4  & 1 & -1 & | & 2 \\
        -2 & 1 & 3  & | & 3
    \end{bmatrix}
\]
```

or 

```tex 
\[
    \begin{bmatrix}
        2  & 3 & 1  & \mid & 1 \\
        4  & 1 & -1 & \mid & 2 \\
        -2 & 1 & 3  & \mid & 3
    \end{bmatrix}
\]
```

to 

```tex
\[
    \left[
    \begin{array}{ccccc|c}
        0 & 0 & 0 & \frac{3}{2} & 1 & 36 \\ 
        0 & 0 & 1 & \frac{1}{3} & \frac{-1}{3} & 2 \\ 
        0 & 1 & 0 & \frac{1}{2} & 0 & 6 \\   
        1 & 0 & 0 & \frac{-1}{3} & \frac{1}{3} & 2
    \end{array}
    \right]
\]
```

--- 

## Constraints 

- You are not alloweed to make other modifications except for the specified task.

- You can only edit one file at a time.

- You need to point out the lines in the chat of the changes you made.

- The target files are: 
    - Linear_Systems_of_Equations.tex
    - Matrices.tex

which are both in [./src/Linear_Algebra].

