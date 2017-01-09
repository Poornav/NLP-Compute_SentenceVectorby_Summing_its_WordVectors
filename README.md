NLP -- Constucting a Sentence vector by summing its word vectors.

Algorithm :

1. Take each sentence and get the word vectors for each word in the sentence .

2. Constuct a Sentence vector by summing its word vectors and normalizing by dividing the norm of the vector

3. Use the sentence vectors to determine the semantic similarity between sentences and produce the summary based on the semantic similarity.

4. Create a table that has the cosine sililarity value between all sentences si, sj.