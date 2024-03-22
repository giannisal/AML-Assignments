The attached assignment is split in three individual Jupyter notebooks.

On the first jupyter notebook (greek_parliament_t8150002_total_preprocessing), 
there is included the initial reading and filtering of the data, as well as the whole data exploration. 
This includes charts and tables, as well as commands that aim to the understanding of the dataset, its meaning and it contents.

On the second jupyter notebook (greek_parliament_t8150002_traditional_ML), we remove all exploratory cells,
and only include the ones where we actualy need for the data manipulation.
Also, for memory efficiency purposes, we avoid creating new columns when not necessary, and either replace pre-existing columns
(political_party mapping to integer - instead of political_id column, speech turned to list instead of speech_tokened column)
or temporarily calculate them to display their outputs (speech_set, measuring the unique words per speech.)

On the third notebook (greek_parliament_t8150002_nn), we follow a similar approach, but include the necessary exploratory cells
in order to identify the optimal initial hyperparameters for our neural networks. We also follow the column efficiency approach, as in the second file.

REVISED VERSION:
The correct version of the neural network file (previously read as greek_parliament_t8150002_nn, currently greek_parliament_t8150002_neural_disambiguation) 
has been added, to fix a wrongful file inclusion with the previous delivery.

On the fourth file (parliament_text_generation_t8150002), we implement a text generation approach based on the example provided during the lectures.