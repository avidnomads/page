# Projects

## Python

[Old School RuneScape Bots](https://github.com/djmot/osrs)

A collection of botting programs for the video game Old School RuneScape (OSRS). These programs use pixel and image searching to perform a set of tasks in the game. So far the main libraries in use are PyAutoGui for keyboard/mouse automation and image searching, PIL for image searching and manipulation, and Tkinter for GUI elements. Human-like mouse and keyboard inputs, including replication of actual human mouse moves, are used to closely simulate a real player. Currently there is a woodcutting bot, a script to register new accounts, a bot to complete the tutorial portion of the game, and a bot that uses banking/Grand Exchange trading utilities to acquire supplies on new accounts.

Check out a YouTube video of the bots in action by clicking the image below.

[![OSRS bot](/images/osrsbot.png)](https://www.youtube.com/watch?v=kuUoJRoRcMU "osrs demo")

---

[Black-Litterman model implementation](https://github.com/djmot/BLP)

An implementation of the Black-Litterman model, which estimates the distribution of expected excess returns of a collection of asset classes. By using historical return data for a collection of asset classes and incorporating our own views about the future returns, we can generate an estimate of the future distribution of returns and, therefore, an optimal portfolio in these asset classes (optimal in the sense of maximizing the Sharpe ratio of the portfolio).

An example is provided in the github repository.

![blp_image](/images/blp.PNG)

(image from Idzorek (2005): "A STEP-BY-STEP GUIDE TO THE BLACK-LITTERMAN MODEL" which is also a great resource for understanding and using the Black-Litterman model)

---

## Javascript/HTML/CSS

#### Online apps

These are online applications built in JavaScript using Node, Express, React (a UI library), and MongoDB (a NoSQL database program).



[Stocks (https://stocks-djmot.herokuapp.com/)](https://stocks-djmot.herokuapp.com/)
![stocks screenshot](/images/stocks.png)

Users can look up and graph the prices of stocks. 
Users can add and remove stocks and compare several at a time.

---

[Nightlife (https://night-life-djmot.herokuapp.com/)](https://night-life-djmot.herokuapp.com/)
![nightlife screenshot](/images/nightlife1.png)

Users can search for local bars and entertainment venues.
Users can log in with Twitter and then register that they plan to go to a venue.

---

[Voting (https://voting-djmot.herokuapp.com/)](https://voting-djmot.herokuapp.com/)
![voting screenshot](/images/voting.png)

Users can view and vote on polls created by other users, and see the results. 
Users can log in using their Twitter accounts and create their own polls.

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

[Cayley graphs of Burnside groups](https://github.com/djmot/burnside-graphs)

The Burnside group B(m,n) is defined to be the largest group with m generators and exponent n. Burnside's problem is to determine which of the groups B(m,n) are finite. For example, it is known that the groups B(m,3), B(m,4), and B(m,6) are finite. One way to show that a group is finite is to construct its Cayley graph, since the graph has one vertex for each element of the group. This program attempts to compute the Cayley graph of the group B(2,n) and print the order of the group. For example, B(2,3) is a group of order 27, whose Cayley graph is depicted below. An interactive drawing (which omits the direction of edges) can be found here: [https://codepen.io/djmot/full/apKmEw/](https://codepen.io/djmot/full/apKmEw/)

![B(2,3) Cayley graph](/images/b23graph.png)
