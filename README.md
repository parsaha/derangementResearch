# On the derangement of n-card decks and their subsets

## Problem

Rencontres is an old French card game in which the 52 cards of a deck are laid out, with another deck of 52 being laid out randomly on top of the first so that there are 52 piles of 2 cards. The score is determined by counting the number of matching pairs. In 1708, Pierre Raymond de Mort posed the question of what the probability of not scoring at all (that is, no pair being a match) is. 
Mathematically, we think of this problem as having decks ![equation](https://latex.codecogs.com/gif.latex?A) and ![equation](https://latex.codecogs.com/gif.latex?B), each with 52 cards, are laid out (first the cards of deck ![equation](https://latex.codecogs.com/gif.latex?A), then deck ![equation](https://latex.codecogs.com/gif.latex?B)). Then, what is the chance no cards are the same in each pair?

## Derangements

**Definition:** A derangement of ![equation](https://latex.codecogs.com/gif.latex?%5C%7B1%2C2%2C%5Cdots%2C%20n%5C%7D) in which the location of each in the integers is a permutation ![equation](https://latex.codecogs.com/gif.latex?i_1i_2%5Cdots%20i_n) of ![equation](https://latex.codecogs.com/gif.latex?%5C%7B1%2C2%2C%5Cdots%2C%20n%5C%7D) such that ![equation](https://latex.codecogs.com/gif.latex?i_1%20%5Cneq%201%2C%20i_2%20%5Cneq%202%2C%20%5Cdots%2C%20i_n%20%5Cneq%20n). Thus, a derangement of ![equation](https://latex.codecogs.com/gif.latex?i_1i_2%5Cdots%20i_n) is a permutation of ![equation](https://latex.codecogs.com/gif.latex?i_1i_2%5Cdots%20i_n) such that no integer is in its natural position. 


Since we can think of our problem as relating to derangements, we can make use of the following result, cited in the paper:

**Theorem:** The number ![equation](https://latex.codecogs.com/gif.latex?%5Cmathcal%7BD%7D_n) of derangements of a set ![equation](https://latex.codecogs.com/gif.latex?A%20%3D%20%5C%7B1%2C%20%5Cldots%2C%20n%5C%7D) is given by ![equation](https://latex.codecogs.com/gif.latex?%5Cmathcal%7BD%7D_n%20%3D%20n%21%20%5Cleft%28%201%20-%20%5Cfrac%7B1%7D%7B1%21%7D%20&plus;%20%5Cfrac%7B1%7D%7B2%21%7D%20-%20%5Cfrac%7B1%7D%7B3%21%7D%20&plus;%20%5Cdots%20&plus;%20%28-1%29%5En%20%5Cfrac%7B1%7D%7Bn%21%7D%5Cright%29).


Expanding on this result, the paper concludes with a corollary, answering the original question:

**Corollary:** The probability that there are no two pairs when one deck of ![equation](https://latex.codecogs.com/gif.latex?n) cards is randomly placed on top of another deck is ![equation](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cmathcal%7BD%7D_n%7D%7Bn%21%7D%20%3D%20%5Cfrac%7B%7B%7D%5CBigg%5B%5Cfrac%7Bn%21%7D%7Be%7D%5CBigg%5D%7D%7Bn%21%7D%20%5Capprox%20%5Cfrac%7B1%7D%7Be%7D.)


Furthermore, the paper investigates the question of generalizing the problem beyond 52-card decks sorted into pairs. We found and described the relevance of the study of Latin Rectangles with relation to the generalized problem. 
