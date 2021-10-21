---
title: "Greedy Spanners in Euclidean Spaces Admit Sublinear Separators"
collection: publications
date: 2022-01-07
venue: 'SODA'
paperurl: 'https://arxiv.org/abs/2107.06490'
citation: 'H Le, C Than. (2021). &quot;AGreedy Spanners in Euclidean Spaces Admit Sublinear Separators .&quot; <i>2022 33rd ACM-SIAM Symposium on Discrete Algorithms (SODA22)</i>.'
---
The greedy spanner in a low dimensional Euclidean space is a fundamental geometric construction that has been extensively studied over three decades as it possesses the two most basic properties of a good spanner: constant maximum degree and constant lightness.  Recently, Eppstein and Khodabandeh showed that the greedy spanner in $\mathbb{R}^2$ admits a sublinear separator in a strong sense: any subgraph of $k$ vertices of the greedy spanner in $\mathbb{R}^2$ has a separator of size $O(\sqrt{k})$.  Their technique is inherently planar and is not extensible to higher dimensions. They left  showing the existence of a small separator for the greedy spanner  in $\mathbb{R}^d$ for any constant $d\geq 3$  as an open problem. 

In this paper, we resolve the problem of Eppstein and Khodabandeh by showing that any subgraph of  $k$ vertices of the greedy spanner in $\mathbb{R}^d$ has a separator of size $O(k^{1-1/d})$. We introduce a new technique that gives a simple characterization for any geometric graph to have a sublinear separator that we dub \emph{$\tau$-lanky}: a geometric graph is  $\tau$-lanky if any ball of radius $r$ cuts at most $\tau$ edges of length at least $r$ in the graph. We show that any $\tau$-lanky geometric graph of $n$ vertices in $\mathbb{R}^d$ has a separator of size $O(\tau n^{1-1/d})$. We then derive our main result by showing that the greedy spanner is $O(1)$-lanky. We indeed obtain a more general result that applies to unit ball graphs and point sets of low fractal dimensions in $\mathbb{R}^d$.

Our technique naturally extends to doubling metrics. We use the $\tau$-lanky characterization to show that there exists a $(1+\epsilon)$-spanner for doubling metrics of dimension $d$ with a constant maximum degree and  a separator of size $O(n^{1-\frac{1}{d}})$;  this result resolves an open problem posed by Abam and Har-Peled a decade ago. We then introduce another simple characterization for a graph in doubling metrics of dimension $d$ to have a sublinear separator. We use the new characterization to show that the greedy spanner of an $n$-point metric space of doubling dimension $d$  has a separator of  size $O((n^{1-\frac{1}{d}}) + \log\Delta)$ where $\Delta$ is the spread of the metric; the factor $\log(\Delta)$ is tightly connected to the fact that, unlike its Euclidean counterpart, the greedy spanner in doubling metrics has \emph{unbounded maximum degree}. Finally, we discuss algorithmic implications of our results.

[Download paper here](https://arxiv.org/abs/2107.06490)
