# Patient-Condition-Classification-Using-Drug-Reviews

![image](https://github.com/Day-Raval/Patient-Condition-Classification-Using-Drug-Reviews/assets/132192767/7f2282a2-d0e1-4034-b0bd-9c131f056c49)

Reviews are important to get the overview of products whether it is a service, offerings or products. Reviews also play an important role in healthcare domain especially in terms of drugs. By analyzing the reviews, we can get the drug effectiveness and its side effects.We build a system that can classify a patient's condition by the help of both Natural Language Processing(NLP) and Machine Learning(ML) based on his review so that we can recommend him a suitable drug 

Steps of NLP Pipeline:-
1. Tokenize the sentences
2. Clean reviews:
     a) Remove punctuation
     b) Remove special characters/numbers
     c) Convert to lowercase
     d) Lemmitization
3. Create a bag of words to vectorize
4. Apply ML algos Naive Bayes & Passive Aggressive Classifier
5. Create a TFIDF model to vectorize
6. Apply ML algos Naive Bayes & Passive Aggressive Classifier
7. Compare the results based on (5)
