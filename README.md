## Comparing the Powerhouses: A Battle of Three-Layered Neural Networks with Word Embeddings and Fine-Tuned BERT Model for Text Classification (Tweets)

This project aims to investigate the efficacy of various embedding techniques in the classification of hate speech. We compare different embedding methods to assess their impact on the accuracy and efficiency of hate speech classification models. Our goal is to offer valuable insights into the performance of these embedding methods and provide a framework for future research in this area.
Research Questions

    Which embedding method(s) perform best for hate speech classification, and why?
    How do different embedding methods affect the accuracy, precision, recall, and F1-score of hate speech classification models?
    How does it compare to the performance of BERT embeddings with its own preprocessing methods?

### Model Structures

We compared a simple classifier with a BERT classifier, using different types of embeddings including TF-IDF, Bag of Words (BoW), Spacy, Word2Vec (average, sum, and concat), FastText, and BERT.
Results

The differences in the evaluation metrics between the different embeddings appear to be relatively small. The choice of embedding method does not have a large impact on the overall performance of the model. The BERT model's training accuracy and validation accuracy increase significantly as the number of training points increases, indicating that the model is learning better with more data. As test accuracy shows, the fine-tuned BERT model outperforms other models by about 0.8 percent.
Conclusions

Further analysis, such as individual example prediction examination and t-SNE visualization of the embeddings, can provide a deeper understanding of the differences between the embeddings and their impact on the model's performance.

### Authors

    Sayyed Ahmad Hosseini
    Sithursan Sivasubramaniam

### Acknowledgements

We would like to thank everyone who contributed to this project and provided valuable insights and feedback.

Remember to replace the placeholders with the actual information, such as the installation instructions, usage, and contributions.