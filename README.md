# Embedding-Based-Sentiment-Classification

This readme provides an overview of a embedding based sentiment classification that utilizes embeddings for text data. The classifies text reviews into sentiment categories based on cosine similarity scores with predefined positive and negative embeddings.

## Workflow

1. **Embeddings Generation**: The notebookt generates embeddings for input review text using a pre-trained language model.

2. **Similarity Calculation**: It calculates the cosine similarity of the text embedding with both positive and negative label embeddings.

3. **Classification**: The text is classified as 'positive' or 'negative' based on which label embedding it is most similar to.

4. **Performance Metrics**: The performance is evaluated using a precision-recall curve, and the results are presented with the corresponding Area Under Curve (AUC) score.

### Precision-Recall Curve

![newplot](https://github.com/TKaanKoc/Embedding-Based-Classification/assets/83168207/3a65b935-dc7b-4d88-a9dd-a817e15fbe46)

*The Precision-Recall Curve with an AUC score of 0.98 indicates the model's high performance in sentiment classification.*

### Classification Table

<img width="1217" alt="image" src="https://github.com/TKaanKoc/Embedding-Based-Classification/assets/83168207/a3896666-63af-4264-94fa-63596a7ee885">

*The classification table shows sample texts with their respective classifications and similarity scores. Each text is compared against positive and negative label embeddings, and the classification is done based on the higher similarity score.*

## Conclusion

The implemented sentiment classification model effectively categorizes text reviews using embedding-based similarity measures. The high AUC value reflects the model's reliability in distinguishing between positive and negative sentiments.
