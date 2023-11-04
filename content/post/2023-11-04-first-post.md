---
title: First Post
date: '2023-11-04'
categories:
  - Example
tags:
  - Markdown
---

I am in love with this new extremely minimal theme designed by [Yihui](https://github.com/yihui/hugo-xmin). It also supports LaTeX math expressions. Here is the induction axiom for structural induction on type `$\tau$`, that I just copied from our current draft on Overleaf:

`$$
    \biggl(
            \bigwedge_{c \in \Sigma_{\tau}}
            \Bigl[
                \forall_{i = 1}^{n_c} y_{c,i} .
                \forall_{k \in P_c} w_{c,k} .
                \exists u_c .
                    \bigl(
                        (\bigwedge_{j \in P_c} L[y_{c,j}, w_{c,j}]) \rightarrow L[c(\bar{y_c}), u_c]
                    \bigr)
            \Bigr]
    \biggr)
    \rightarrow
    \forall z .\exists x. L[z, x]
$$`

Wonderful! Isn't it?