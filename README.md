# Pokemon-Battle-Outcome
To delve deep into the battle mechanics of Pokemon, that is, to understand the
possibility of one pokemon gaining victory over the other, we assign pokemons moves
based on their typing and using the type-chart dataset, we check the effectiveness of
certain types of moves. We have assumed that the move-type effectiveness factor has
a significant impact over the health power of the pokemon, which if drops to zero, the
opposing pokemon wins. However, we have filtered the opponent selection procedure
by clustering, based on the assumption that pokemon with similar action and defense
stats will be better suited to be more effective at battling a particular pokemon. To check
this, an approximate “Win” or “Lose” label is assigned that enables us to estimate the
probability of success and failure. Using the k-means clustering algorithm, we have
filtered all the pokemon into 7 clusters based on their stats. This is followed by a
randomizer which selects 2 pokemon belonging to the same cluster and simulates a
battle with our assumptions and then we check the corresponding probabilities of victory
using Gaussian Naive Bayes algorithm and check the accuracy of the said algorithm in
order to compare it with the traditional battle outcome based on type effectiveness.

# Procedure
Download the moves.csv, pokemon.csv, type-chart.csv and Pokemon.ipynb
After that run your code in Jupyter Notebook to see the data analytics and the model built

## (Note: You can refer to the additional README in the files section for better guidance)
