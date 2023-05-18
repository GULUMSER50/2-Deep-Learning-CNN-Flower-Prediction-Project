# Deep-Learning-CNN-Flower-Prediction-Project
Deep learning - CNN used to predict the class of flowers

<img width="698" alt="Screenshot 2023-05-18 at 13 31 30" src="https://github.com/GULUMSER50/Deep-Learning-CNN-Flower-Prediction-Project/assets/108715553/b95a37a7-cfe1-4fd0-a31e-3f265040d378">

# Summary of Flower Recognition CNN

In my project, I developed a flower classification algorithm using Convolutional Neural Networks (CNN). The dataset consisted of images from five different classes of flowers. To train and evaluate my model, I split the original dataset into three groups: train, validation, and test. I performed the split using ratios of 0.7, 0.2, and 0.1, respectively.

During the training phase, I monitored the performance of my model across multiple epochs. I optimized the model's parameters to minimize the loss function. As the training progressed, I observed a gradual decrease in the loss values, indicating that my model was learning and improving its predictions.

I also evaluated my model using the validation set, which provided an unbiased estimate of its performance on unseen data. The validation results showed the accuracy and loss values of my model at each epoch. By comparing the training and validation performance, I gained insights into potential overfitting.

Additionally, I utilized classification metrics such as precision, recall, and F1-score to evaluate my model's performance on the validation set. The classification report provided a detailed breakdown of these metrics for each class, enabling me to assess the precision in correctly identifying positive instances, recall in capturing actual positive instances, and the overall F1-score.

Furthermore, I analyzed the confusion matrix, which revealed the distribution of correctly classified and misclassified instances for each class. By studying the confusion matrix, I could identify any patterns or specific classes where my model struggled or exhibited confusion.

Based on the evaluation metrics, my model achieved an accuracy of 67% on the test set. The precision, recall, and F1-score varied across the classes, with an average weighted F1-score of 0.67. These metrics provide insights into my model's performance on each class and its overall effectiveness in flower classification.

To further improve my model, I can analyze the confusion matrix to identify specific areas of misclassification and focus on enhancing my model's performance on those classes. Additionally, monitoring and addressing any signs of overfitting, such as a significant gap between training and validation performance, can help ensure the generalization of my model to unseen data.

Overall, my project demonstrates the successful development and evaluation of a CNN-based flower classification algorithm. The insights gained from the evaluation metrics and confusion matrix can guide future enhancements and fine-tuning of my model to improve its performance on specific flower classes.




