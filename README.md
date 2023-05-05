Download Link: https://assignmentchef.com/product/solved-cse225-project-2-ternary-search-tree-tst
<br>



This project is a programming assignment in C which aims to write an algorithm that will build a <em>ternary search tree</em> (TST) and makes necessary operations in this tree.

<ol>

 <li>(40 points) Consider a TST where the only difference with a binary search tree is that a key that is greater than the current node’s key but less than or equal to the square of it is located at the middle child of the node. More formally expressed,</li>

</ol>

<em>Key(LC<sub>A</sub>) &lt; Key(A) &lt; Key(MC<sub>A</sub>) ≤ (Key(A))<sup>2</sup> &lt; Key(RC<sub>A</sub>)</em>

where <em>A</em> represents the current node, <em>LC<sub>A</sub></em>, <em>MC<sub>A</sub></em> and <em>RC<sub>A</sub></em> denote the left child, the middle child and the right child of <em>A</em>, in respective order.

<strong><em>Write a recursive insert function that inserts a list of keys given you as an input file in the above TST!     </em></strong>

<em>Hint: Both the node structure and the function should be very similar to that of the binary search tree in your lecture notes. </em>

<ol>

 <li>(40 points) Write a remove function that searches for a given key in the above TST given in (a) and remove it and finally re-build the TST!</li>

</ol>

<em> </em>

<ol>

 <li>(20 points) Write a recursive <em>find</em> function that searches for a given key in the above TST given in (a)!</li>

</ol>

<em> </em>

<ol>

 <li>(50 points- <strong>BONUS</strong>) In (a), (b) and (c) parts the formula is given and you are expected to do the necessary operations. This time, find a formula that makes the tree has a <strong><em>minimum depth level</em></strong>. Before starting implementation, studying mathematical proof of this question will be useful for you. After you decide the formula, implement the (a), (b) and (c) parts.</li>

</ol>

1







<strong>The main goal of this project is to be familiar with Trees. So, if you use arrays/linked lists instead of Trees then you will get zero, unfortunately.</strong>

In this project you are expected to develop an algorithm that is capable of finding a solution to the above problem and <strong><em>implement this algorithm in ANSI C that runs under either UNIX or Windows</em></strong>.