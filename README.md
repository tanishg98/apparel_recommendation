# Apparel Recommendation
 A Recommender system that recomends apparel based on image and text similarity on Amazon API.
 
 All the dataset used is present in the given google drive link
https://drive.google.com/drive/folders/0BwNkduBnePt2VWhCYXhMV3p4dTg

Various pickle files are saved at various checkpoints of the jupyter notebook,so that if u get struck anywher you could run those pickled data file and continue.

Text similarity is done on the description using various techniques like TF-IDF,IDF,Word2Vec,gensim model etc. , you can choose wahtsover technique you like ,mostly IDF works best.For Image similarity Keras has been used.
To comapre the similarity between two feature vectors pairwise_distribution is uded which calculates the euclidean distance,the similar ones will have a small distance.
For testing A/B testing is used,which is one of the most popular ones

Refrences:
https://medium.com/@humansforai/recommendation-engines-e431b6b6b446
https://www.appliedaicourse.com/
