# Automated-Answer-Evaluation
This project makes use of pretrained transformers to get the contextual embeddings of the text taken as input.
In the context of this project, answers to a question are taken as text input and their contextual embedding is
generated and compared with the embeddings of the actual answer achieved by the same process. Cosine similarity is used
to calculate the semantic similarity between the two texts. If the answer is close to the actual answer, then the similarity
score will be high.
