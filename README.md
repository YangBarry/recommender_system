# Recommender System for Amazon

This collaborative project, undertaken in partnership with Peilin Liu and Guang Yang, focuses on enhancing recommender systems. Our endeavor involves the creation of a sophisticated deep recommender system tailored for Amazon's platform. The innovative neural network architecture we have designed facilitates the computation of the compatibility level between various user-product pairs, leveraging multimodal data. This neural network forms the central computational engine of a robust large-scale recommender system. Let me highlight the cool features of our model: 
- Multimodal: We consider diverse and unstructured data sources, including tabular (product features), text (reviews and text description), and image (product images).
- Deep & Wide Model: Our algorithm is built on top of the Google Wide & Deep model. The main idea is to connect the Wide part of the single input layer and the Deep part of the multi-layer perceptron. Then, combine the output together and feed it into a fully-connected output layer.
- Memorization and generalization: Memorization and generalization co-exists in our model. The Deep network is good at memorization, and the Wide network is good at generalization.  

In this GitHub repo, you can find our codes and a report accompanying our proposed deep recommender model. 
