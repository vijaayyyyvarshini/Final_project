# Final_project

Parts-of-speech (POS) tagging is a process of marking each word in a text corpus with its corresponding POS tag, such as noun, verb, adjective, adverb, etc. In Tamil, the process of POS tagging is similar to other languages.

The Hidden Markov Model (HMM) is a statistical model that can be used for POS tagging. The HMM assumes that the underlying sequence of POS tags is a Markov process, meaning that the probability of a given tag depends only on the previous tag, rather than the entire history of tags.

The Viterbi algorithm is an efficient method for finding the most probable sequence of POS tags for a given text corpus. The algorithm starts by computing the probability of each tag for the first word in the corpus, then iteratively calculates the probability of each subsequent tag based on the previous tag and the observed words. The final result is the most probable sequence of tags.

In summary, HMM and Viterbi algorithm can be used for POS tagging in Tamil by assuming a Markov process for the underlying sequence of tags and finding the most probable sequence of tags using the Viterbi algorithm.

My model attained an accuracy of 93%
