
<h1> CS3014 Parallel sort algorithm </h1>

<p>
This is an assignment for a third year computer science class 'Concurrent Systems 1' completed by myself and Joel Coffey.  The task for this assignment was to implement a sorting algorithm of our choice to sort large arrays of 32-bit integers.  The only requirement was that we were expected to utilize OpenMp parallelization to improve the runtime of the algorithm.
</p>

<h1> Algorithm used </h1>

<p>
We based our algorithm on <a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.31.6231"> Parallel Sorting by Regular Sampling.</a>  The spec of the base algorithm can be found at the link provided.  Our algorithm also incorporates standard <em>mergesort</em> and <em>insertion sort</em>, as well as variouse optimizations surrounding OpenMp overheads.  The algorithm is geared towards large array sizes (> 1,000,000).
</p>

<h1> Runtime and Honours </h1>
<p>
Each team had to demonstrate their code running on random arrays of various sizes. 
Our times:
<ul>
<li>10,000,000 | 296,601µs</li>
<li>100,000 | 10,948µs</li>
<li>1,000 | 204µs</li>
</ul>

This code won the competition and recieved full marks for the assignment
</p>