# sequential-group-recommendation


<p>This work is based on the assignment that were given on Tampere University's Recommender System class. The goal of this expirements is to find the method that is the most fair between the users in the group. Fairness in group recommendation is to produce recommendation that minimize the user disagreement between users in the group. The concept of group aggregation such as average method (Averaging rating of the same movie between users) and least misery method (Taking the lowest rating between users of an item that they have in common) </p>

<p>
In this assignment I implemented the paper "Fair Sequential Group Recommendations" by Maria Stratigi, Jyrki Nummenmaa, Evaggelia Pitoura,
and Kostas Stefanidis and experiment with the modification and comparison between the results of the implementation. This implementation is based on collaborative filtering method using user based similarity</p>

<p>I would give an appreciation Neil Patel, my classmate with whom I spent a good amount of time to understand the assignment,
formulating the challenges, exchanging ideas, and in the end each of us could produce proper implementations, solutions, and method. </p>

<a href="https://homepages.tuni.fi/konstantinos.stefanidis/docs/sac20.pdf">Link to the paper </a>
<br>
Jupyter Notebook files:
<ul>
<li>First-method-paper</li>
<li>Second-method-kendall-tau</li>
<li>Third-method-standard deviation</li>
</ul>

The result of this experiment is presented in the file Results: Sequential GR Recommender Systems.pdf

<p>To be able to run the notebook, install these python libraries:</p>
<ul>
<li><a href="https://anaconda.org/anaconda/pandas">Pandas</a> </li>
<li><a href="https://anaconda.org/anaconda/scipy">Scipy</a></li>
<li><a href= "https://anaconda.org/conda-forge/matplotlib">Matplotlib</a></li>
<li><a href="https://anaconda.org/anaconda/numpy">Numpy</a></li>
</ul>

