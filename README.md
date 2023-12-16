# NLP-for-Verbal-Autopsies

The interest in designing algorithms that learn from themselves, or machines
that understand their environment and adapt to it, is increasing as computer
science advances. These practices are encompassed under the term Artificial
Intelligence (AI).
One discipline within AI, and one of the booming fields, is called Natural
Language Processing (NLP). In this field, the main goal is for a computer
to understand, analyze, manipulate and potentially generate human natural
language. In general, the NLP deals with trying to understand written texts
from different points of view, such as answering questions, locating similar
texts, extracting relevant words, etc. In this work we are going to focus on
the search for similar texts. For this we will use one of the most widespread
techniques in the field of word processing which is word embedding, with
the intention of transforming the texts into vectors with which to carry out
algebraic operations. This approach is based on the idea of assigning to each
word of a text a dense vector of variable dimension, called embedding, which
has semantic information about the word it represents.
Thus, in this work we will thoroughly explain the idea behind word embedding. We will show how the explicit calculation of these dense vectors
is carried out by designing the neural network from scratch, to later use
it in the calculation of the semantic similarity between texts, as well as to
study and optimize its operation in this task. For the latter, we will test the
embeddings in a specific corpus of a medical type based on verbal autopsies
(VA). On this corpus, experiments will be carried out with the intention of
both testing the usefulness of embeddings and trying to make improvements
to existing studies with respect to VAs that we will present below.
