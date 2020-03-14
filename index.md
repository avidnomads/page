# Projects

[Studious (https://studious-carrot.herokuapp.com/)](https://studious-carrot.herokuapp.com/)
![studious screenshot](/images/studious.png)

Studious is a platform for creating, reviewing, and sharing lessons which implements a [spaced repetition system](https://knowledge.wanikani.com/wanikani/srs/) for efficient reviews.
Built with Django, PostgreSQL, and pure JavaScript.

---

[Old School RuneScape Bots](https://github.com/djmot/osrs)

A collection of botting programs for the video game Old School RuneScape. These are "color bots" which read and search the game canvas and interact using human-like mouse and keyboard inputs. Built in Python using PyAutoGui, PIL and Tkinter. Currently there is a woodcutting bot, a script to register new accounts, a bot to complete the tutorial portion of the game, and a bot that uses banking/Grand Exchange trading utilities to acquire supplies on new accounts.

Check out a [video](https://www.youtube.com/watch?v=kuUoJRoRcMU "osrs demo") of the bots in action:
[![OSRS bot](/images/osrsbot.png)](https://www.youtube.com/watch?v=kuUoJRoRcMU "osrs demo")

---

[Notebooks](https://github.com/dmjz/notebooks)

A few fun mathematical Jupyter notebooks:

1. monte_carlo_areas

Compute and plot some interesting areas in plan geometry by random sampling

2. multiplication_methods

Explore algorithms for fast multiplication

3. predicting_loan_default

Naive hyperparameter selection with LendingClub data

![monte_carlo_areas](/images/mandelbrot.png)

---

[Nightlife (https://night-life-djmot.herokuapp.com/)](https://night-life-djmot.herokuapp.com/)
![nightlife screenshot](/images/nightlife1.png)

Search for local bars, restaurants, and more and see where everyone else is going. Built with Node/Express and integrated with Twitter for authentication and Yelp to search local venues.

---

[Black-Litterman model implementation](https://github.com/djmot/BLP)

A Python implementation of the Black-Litterman model, which estimates the distribution of expected excess returns of a collection of asset classes. By using historical return data for a collection of asset classes and incorporating our own views about the future returns, we can generate an estimate of the future distribution of returns and, therefore, an optimal portfolio in these asset classes (optimal in the sense of maximizing the Sharpe ratio of the portfolio).

A detailed example is provided in the [github repository.](https://github.com/djmot/BLP)

![blp_image](/images/blp.PNG)

(image from Idzorek (2005): "A STEP-BY-STEP GUIDE TO THE BLACK-LITTERMAN MODEL" which is also a great resource for understanding and using the Black-Litterman model)

---

[Voting (https://voting-djmot.herokuapp.com/)](https://voting-djmot.herokuapp.com/)
![voting screenshot](/images/voting.png)

Create and vote in online polls, and see the results in a simple (but elegant) display. Built with Node/Express/MongoDB, Chart.js, and Twitter API for authentication.

---

[Text analysis of SEC filings](https://github.com/dmjz/sec-embed)

In this project we use word embedding to produce features from the natural language content of SEC filings and test the effect of these features on stock price movement. We use Python for web scraping, topic analysis, and data visualization, and PyTorch to build and train a neural network for word embedding. 

![word embed](/images/model_arch.png)

---

[Particle collision simulation (https://codepen.io/djmot/full/XNQEBy/)](https://codepen.io/djmot/full/XNQEBy/)
![particle screenshot](/images/particle.png)

Run a variety of different particle collision simulations built with pure JavaScript. Particle collisions are predicted and handled efficiently using a priority queue. 

---

[React Game of Life (https://codepen.io/djmot/full/gLObxz/)](https://codepen.io/djmot/full/gLObxz/)
![life screenshot](/images/life.png)

An implementation of Conway's Game of Life in JavaScript/React. Pause the game, create a new pattern, and see how it evolves.

---

[Orientable embeddings of Cayley graphs](https://github.com/djmot/orientable-embeddings)

In my Master's thesis I give an algorithm to compute all the embeddings of a finite Cayley graph in any surface. This program implements the algorithm (restricting to orientable embeddings) for a selection of Cayley graphs, and counts how many of the embeddings yield an orientable surface of genus k (for each possible k). Here are some of the computed results: 

![embedding counts table](/images/thesistable.png)

---

[Hamiltonian paths in grid graphs](https://github.com/djmot/grid-paths)

A Hamiltonian path in a grid graph is a path in an m x n rectangular grid that hits each point of the grid exactly once. Let G(m,n) be the number of such paths starting at a given corner. This program computes G(m,n) as well as two related numbers: O(m,n), the number of paths which end at the opposite corner to the starting corner, and A(m,n), the number of paths which end at the corner adjacent to the starting corner via the length-m side. These numbers are computed and stored in three tables in CSV format. 

A portion of the A(m,n) table for m, n less than 8:
![grid path table](/images/gridtable.png)

---

[Cayley graphs of Burnside groups](https://github.com/djmot/burnside-graphs)

The Burnside group B(m,n) is defined to be the largest group with m generators and exponent n. Burnside's problem is to determine which of the groups B(m,n) are finite. For example, it is known that the groups B(m,3), B(m,4), and B(m,6) are finite. One way to show that a group is finite is to construct its Cayley graph, since the graph has one vertex for each element of the group. This program attempts to compute the Cayley graph of the group B(2,n) and print the order of the group. For example, B(2,3) is a group of order 27, whose Cayley graph is depicted below. An interactive drawing (which omits the direction of edges) can be found here: [https://codepen.io/djmot/full/apKmEw/](https://codepen.io/djmot/full/apKmEw/)

![B(2,3) Cayley graph](/images/b23graph.png)
