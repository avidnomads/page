# Welcome to my portfolio


Hi! My name is David Mason. Here are a few of the things I've worked on.


## Javascript/HTML/CSS

#### Online apps

These are online applications built in JavaScript using Node, Express, React (a UI library), and MongoDB (a NoSQL database program).



[Stocks (https://stocks-djmot.herokuapp.com/)](https://stocks-djmot.herokuapp.com/)
![stocks screenshot](/images/stocks.png)

Users can look up and graph the prices of stocks. 
Users can add and remove stocks and compare several at a time.

---

[Voting (https://voting-djmot.herokuapp.com/)](https://voting-djmot.herokuapp.com/)
![voting screenshot](/images/voting.png)

Users can view and vote on polls created by other users, and see the results. 
Users can log in using their Twitter accounts and create their own polls.

---

[Nightlife (https://nightlife-djmot.herokuapp.com/)](https://nightlife-djmot.herokuapp.com/)
![nightlife screenshot](/images/nightlife1.png)

Users can search for local bars and entertainment and see how many other users plan to go to each venue. 
If users log in with Twitter, they can register that they plan to go to a venue.

---

#### Codepen projects

These are smaller projects stored on codepen.io, where you can view and edit the code right in the page by selecting the "Editor View".



[Particle collision simulation (https://codepen.io/djmot/full/XNQEBy/)](https://codepen.io/djmot/full/XNQEBy/)
![particle screenshot](/images/particle.png)

Run a variety of different particle collision simulations. Particle collisions are predicted and handled efficiently using a priority queue. 

---

[React Game of Life (https://codepen.io/djmot/full/gLObxz/)](https://codepen.io/djmot/full/gLObxz/)
![life screenshot](/images/life.png)

An implementation of Conway's Game of Life using React UI library. Try pausing the game and clicking on the board to create a custom pattern and then see how it evolves.

---

[Finding collinear points (https://codepen.io/djmot/full/qqKYaW/)](https://codepen.io/djmot/full/qqKYaW/)
![collinear screenshot](/images/collinear.png)

This program generates some random points in the plane, then finds all sets of collinear points using three different algorithms - a brute force search, a search using JavaScript's Array.sort, and a custom implementation of Mergesort. The computation time for each method is displayed for comparison. 

---

## C++

These C++ projects were written to compute or count mathematical objects.

[Orientable embeddings of Cayley graphs](https://github.com/djmot/orientable-embeddings)

In my Master's thesis I give an algorithm to compute all the embeddings of a finite Cayley graph in any surface. This program implements the algorithm (restricting to orientable embeddings) for a selection of Cayley graphs, and counts how many of the embeddings yield an orientable surface of genus k (for each possible k). Here are some of the computed results: 

![embedding counts table](/images/thesistable.png)

---

[Hamiltonian paths in grid graphs](https://github.com/djmot/grid-paths)

A Hamiltonian path in a grid graph is a path in an m x n rectangular grid that hits each point of the grid exactly once. Let G(m,n) be the number of such paths starting at a given corner. This program computes G(m,n) as well as two related numbers: O(m,n), the number of paths which end at the opposite corner to the starting corner, and A(m,n), the number of paths which end at the corner adjacent to the starting corner via the length-m side. These numbers are computed and stored in three tables in CSV format. For example, here is the portion of the A(m,n) table for m, n less than 8:

![grid path table](/images/gridtable.png)

---

[Cayley graphs of Burnside groups](https://github.com/djmot/burnside-groups)

The Burnside group B(m,n) is defined to be the largest group with m generators and exponent n. Burnside's problem is to determine which of the groups B(m,n) are finite. For example, it is known that the groups B(m,3), B(m,4), and B(m,6) are finite. One way to show that a group is finite is to construct its Cayley graph, since the graph has one vertex for each element of the group. This program attempts to compute the Cayley graph of the group B(2,n) and print the order of the group. For example, B(2,3) is a group of order 27. An interactive drawing of its Cayley graph can be found here: https://codepen.io/djmot/full/apKmEw/
