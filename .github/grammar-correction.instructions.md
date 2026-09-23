# Grammar Correction Rules 

For each of the files in the directory I am going to give you, you are going to `spawn` a sub-agent which is goin to perform the task underneath.

--- 

## Code Base Conventions

This is a code base which consists on different LateX files which explain different math-related topics. 

I have a very repetitive structure for all of my files which is not relevant for the grammar correction, but it
should reamin the same after it. It consists on **chapters**, **sections**, **subsection**, etc.. I always try to keep the document as 
simple as possible.  

--- 

## Task 

### Part I

Due to time constrains and my lack of knowledge of the english language I have found my self having punctuation errors, bad sentence structure, 
no punctuations signs after equations where needed, missing or bad placed commas, etc. 

Your **task** is to first perform a grammatical and linguistic structure analysis of the current **open file** to gain the context of its 
contents, and then afterwards perform the necessary language corrections on it.

If you are not sure about a rule you can use the following link to get an specific rule from the internet: 
- [Grammar Rules](https://www.grammarbook.com/english_rules.asp)

Otherwise you can use your own data and pattern recognition to make the right decisions about the corrections.

### Part II 

You need to transform the  `sections` to `chapter` `subsections` to `sections`, and so on. Note that this is heavely dependent on the context and structure. 
For orientation (Logic)[../src/Discrete/Logic.tex] can help this and the next part. The other part of this task to mark with `emph{}` the first 
apeance of word inside a new section which is related to titile like: `\emph{Matrix multiplication}`. 

My schema is that:

- I put the chapter at the start of the file. **Only one per file**.

- Sections are for topics wide enought to have substopics.

- "Properties of X" tends to be a subsection of another topic and in some cases a section.
  - They are also structured usind `itemize`.

- I use `\textbf` for examples and proof starts, except if it is a topic itself.

- I use title case for all titles, subtitles, etc. It is possible that some titles are not correctly formated.

- Step counts outside dedicated algorithm sections are ok in `\textbf`, if the steps are being listed for the procedure they need to be 
in an `enumerate` enviroment with `subitem` for sub-steps.

#### Examples: 

```tex
\section{Definition of a Matrix}

A \emph{matrix} is a rectangular array of numbers, symbols, or expressions arranged in rows and columns (informally). An 
\(m \times n\) matrix \(A\) consists of \(mn\) elements \(a_{ij}\) where \(i = 1, 2, \ldots, m\) and \(j = 1, 2, \ldots, n\).

Formally, 

\[
    A: m \times n \to \field : (i,j) \mapsto a_{i,j}  
\]
```


```tex
\subsection{Properties Of Matrix Addition And Subtraction}

\begin{itemize}

    \item \emph{Commutativity}: \(A \pm B = B \pm A\).

    \item \emph{Associativity}: \((A \pm B) \pm C = A \pm (B \pm C)\).

    \item \emph{Identity element}: \(A \pm O = A\).
   
    \item \emph{Inverse element}: \(A \pm (-A) = O\).

\end{itemize}
```

--- 

## Constraints

You are **NOT** allowed to: 

- change the meaning or structure of the LaTeX-math unless you are correcting its punctuation or other grammar.
- modify more than one file at a time.

--- 

> If there are no errors you can just notify me and then I will provide you with another file to continue performing the task.

---
