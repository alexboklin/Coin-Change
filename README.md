Suppose we are given a set of positive coin values sorted in ascending order. 
The task is to produce all possible ways of using these coin values in order to produce the given amount. 
Here's an example:
<pre><code>
GHCi> change 7
[[2,2,3],[2,3,2],[3,2,2],[7]]
</code></pre>

**NB:** the order in each combination matters, i.e., [2,2,3] and [2,3,2] are different.
