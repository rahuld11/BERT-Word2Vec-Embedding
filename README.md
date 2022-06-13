# BERT Embedding Vs Word2Vec Embedding

What is Contexulizsed embedding?🤔
How does BERT embedding different from word2vec embedding?

1.Apple is an edible fruit produced by an apple tree.
2.The iPhone is a smartphone made by Apple.

👉 Word Apple has a different meaning in different contexts. But With word embedding like word2vec,
we will have a single embedding or vector representation for the word apple.

👉 BERT uses self-attention to modify default embedding to generate contextualized embeddings.
In simple words, each word in a sentence will have a new embedding with some weighed combination of other words in the sentence.

👉 After the self-attention word, Apple from the first sentence will have embedding more like fruit.
In the second sentence, Apple will have embedding more similar to an organization or company.
