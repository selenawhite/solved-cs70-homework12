Download Link: https://assignmentchef.com/product/solved-cs70-homework12
<br>
Safeway Monopoly Cards

It’s that time of the year again – Safeway is offering its Monopoly Card promotion. Each time you visit Safeway, you are given one of <em>n </em>different Monopoly Cards with equal probability. You need to collect them all to redeem the grand prize.

Let <em>X </em>be the number of visits you have to make before you can redeem the grand prize. Show that

<em> [Hint: Does this remind you of a particular problem? What is the</em>

<em>expectation for this problem?]</em>

<h1>2          Geometric Distribution</h1>

Two faulty machines, <em>M</em><sub>1 </sub>and <em>M</em><sub>2</sub>, are repeatedly run synchronously in parallel (i.e., both machines execute one run, then both execute a second run, and so on). On each run, <em>M</em><sub>1 </sub>fails with probability <em>p</em><sub>1 </sub>and <em>M</em><sub>2 </sub>fails with probability <em>p</em><sub>2</sub>, all failure events being independent. Let the random variables <em>X</em><sub>1</sub>, <em>X</em><sub>2 </sub>denote the number of runs until the first failure of <em>M</em><sub>1</sub>, <em>M</em><sub>2 </sub>respectively; thus <em>X</em><sub>1</sub>, <em>X</em><sub>2 </sub>have geometric distributions with parameters <em>p</em><sub>1</sub>, <em>p</em><sub>2 </sub>respectively. Let <em>X </em>denote the number of runs until the first failure of <em>either </em>machine.

<ul>

 <li>Show that <em>X </em>also has a geometric distribution, with parameter <em>p</em><sub>1 </sub>+ <em>p</em><sub>2 </sub>− <em>p</em><sub>1</sub><em>p</em><sub>2</sub>.</li>

 <li>Now, two technicians are hired to check on the machines every run. They decide to take turns checking on the machines every hour. What is the probability that the first technician is the first one to find a faulty machine?</li>

</ul>

CS 70, Fall 2018, HW 12                                                                                                                                                                        1

<h1>3          Geometric and Poisson</h1>

Let <em>X </em>be geometric with parameter <em>p</em>,<em>Y </em>be Poisson with parameter <em>λ</em>, and <em>Z </em>= max(<em>X</em><em>,Y</em>). Assume <em>X </em>and <em>Y </em>are independent. For each of the following parts, your final answers should not have summations.

(a) Compute <em>P</em>(<em>X </em><em>&gt;Y</em>). (b) Compute <em>P</em>(<em>Z </em>≥ <em>X</em>).

(c) Compute <em>P</em>(<em>Z </em>≤<em>Y</em>).

<h1>4          Darts</h1>

Alvin is playing darts. His aim follows an exponential distribution; that is, the probability density that the dart is <em>x </em>distance from the center is <em>f<sub>X</sub></em>(<em>x</em>) = exp(−<em>x</em>). The board’s radius is 4 units.

<ul>

 <li>What is the probability the dart will stay within the board?</li>

 <li>Say you know Alvin made it on the board. What is the probability he is within 1 unit from the center?</li>

 <li>If Alvin is within 1 unit from the center, he scores 4 points, if he is within 2 units, he scores 3, etc. In other words, Alvin scores b5−<em>x</em>c, where <em>x </em>is the distance from the center. What is Alvin’s expected score after one throw?</li>

</ul>

<h1>5          Exponential Practice</h1>

<ul>

 <li>Let <em>X</em><sub>1</sub><em>,X</em><sub>2 </sub>∼ Exponential(<em>λ</em>) be independent, <em>λ </em><em>&gt; </em> Calculate the density of <em>Y </em>:= <em>X</em><sub>1 </sub>+<em>X</em><sub>2</sub>. [<em>Hint</em>: One way to approach this problem would be to compute the CDF of <em>Y </em>and then differentiate the CDF.]</li>

 <li>Let <em>t </em><em>&gt; </em> What is the density of <em>X</em><sub>1</sub>, conditioned on <em>X</em><sub>1 </sub>+<em>X</em><sub>2 </sub>= <em>t</em>? [<em>Hint</em>: Once again, it may be helpful to consider the CDF P(<em>X</em><sub>1 </sub>≤ <em>x </em>| <em>X</em><sub>1 </sub>+<em>X</em><sub>2 </sub>= <em>t</em>). To tackle the conditioning part, try conditioning instead on the event {<em>X</em><sub>1 </sub>+<em>X</em><sub>2 </sub>∈ [<em>t</em><em>,t </em>+<em>ε</em>]}, where <em>ε </em><em>&gt; </em>0 is small.]</li>

</ul>

<h1>6          Uniform Means</h1>

Let <em>X</em><sub>1</sub><em>,X</em><sub>2</sub><em>,…,X<sub>n </sub></em>be <em>n </em>independent and identically distributed uniform random variables on the interval [0<em>,</em>1] (where <em>n </em>is a positive integer).

<ul>

 <li>Let <em>Y </em>= min{<em>X</em><sub>1</sub><em>,X</em><sub>2</sub><em>,…,X<sub>n</sub></em>}. Find E(<em>Y</em>). [<em>Hint</em>: Use the tail sum formula, which says the expected value of a nonnegative random variable isd<em>x</em>. Note that we can use the tail sum formula since <em>Y </em>≥ ]</li>

 <li>Let <em>Z </em>= max{<em>X</em><sub>1</sub><em>,X</em><sub>2</sub><em>,…,X<sub>n</sub></em>}. Find E(<em>Z</em>). [<em>Hint</em>: Find the CDF.]</li>

</ul>

CS 70, Fall 2018, HW 12