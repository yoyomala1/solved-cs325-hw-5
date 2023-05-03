Download Link: https://assignmentchef.com/product/solved-cs325-hw-5
<br>



<ol>

 <li><em> </em>A region contains a number of towns connected by roads. Each road is labeled by the average number of minutes required for a fire engine to travel to it.  Each intersection is labeled with a circle.  Suppose that you work for a city that has decided to place a fire station at location G. (While this problem is small, you want to devise a method to solve much larger problems).</li>

</ol>




<ul>

 <li>What algorithm would you recommend be used to find the fastest route from the fire station to each of the intersections? Demonstrate how it would work on the example above if the fire station is placed at G.  Show the resulting routes and times<strong>.  </strong></li>

 <li>Suppose one ”optimal” location (maybe instead of G) must be selected for the fire station such that it minimizes the time to the farthest intersection. Devise an algorithm to solve this problem given an arbitrary road map.  Analyze the running time complexity of your algorithm when there are f possible locations for the fire station (which must be at one of the intersections) and r possible roads.</li>

 <li>In the above graph what is the “optimal” location to place the fire station?</li>

 <li>Now suppose you can build two fire stations. Where would you place them to minimize the farthest distance from an intersection to one of the fire stations?  Devise an algorithm to solve this problem given an arbitrary road map.  Analyze the time complexity of your algorithm when there are f possible locations for the fire station (which must be at one of the intersections) and r possible roads.</li>

 <li>In the above graph what is the “optimal” location to place two fire stations?</li>

</ul>

<ol start="2">

 <li><em>(4 points)</em> Consider the following problem:</li>

</ol>

<em>You are given an undirected weighted graph G, two vertices s and t and a weight W; your goal is to find a path from s to t in which every edge has at least weight W.  </em>

<ul>

 <li>Describe an efficient algorithm to solve this problem.</li>

 <li>What is the running time of youor algorithm.</li>

</ul>




<strong>CS 325 – HW 5  </strong><strong> </strong>

<ol start="3">

 <li><em>(</em><em>15 points)</em> Suppose there are two types of professional wrestlers: “Babyfaces” (“good guys”) and “Heels” (“bad guys”). Between any pair of professional wrestlers, there may or may not be a rivalry. Suppose we have n wrestlers and we have a list of r pairs of rivalries.</li>

</ol>

<ul>

 <li>Give pseudocode for an efficient algorithm that determines whether it is possible to designate some of the wrestlers as Babyfaces and the remainder as Heels such that each rivalry is between a Babyface and a Heel. If it is possible to perform such a designation, your algorithm should produce it.</li>

 <li>What is the running time of your algorithm?</li>

 <li><strong>Implemen</strong>t: Babyfaces vs Heels in C, C++ or Python.  Name your program wrestler and include compile and executions instructions in the README file.</li>

</ul>

<strong>Input</strong>:  Input is read in from a file specified in the command line at run time.  The file contains the number of wrestlers, n, followed by their names, the number of rivalries r and rivalries listed in pairs.  <em>Note: The file only contains one list of rivalries</em>

Output:  Results are outputted to the terminal.

          Yes, if possible followed by a list of the Babyface wrestlers and a list of the Heels.       No, if impossible.




<strong>Sample Input file: </strong>

5

Ace

Duke

Jax

Biggs

Stone

6

Ace Duke

Ace Biggs

Jax Duke

Stone Biggs Stone Duke

Biggs Jax




<strong>Sample Output: </strong>

Yes

Babyfaces: Ace Jax Stone

Heels: Biggs Duke

<em>Note: There can be alternative solutions. For consistency assign the first wrestler in the list to be a Babyface. </em>