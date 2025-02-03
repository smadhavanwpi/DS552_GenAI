DS552 - Generative AI
Assignment-2 Instructions:
==========================
Use the Penguins dataset open source dataset, focusing on two species only (e.g., Adelie and Gentoo), to
compare the performance of Naive Bayes (Generative Model) and Logistic Regression (Discriminative Model).
Please ensure to upload your Jupyter Lab Notebook along with the corresponding code and markdown
explanations on GitHub. Once complete, share the repository link for submission.
1. Accuracy Comparison:
• Evaluate and report the accuracy of both the Naive Bayes and Logistic Regression models on the
training and test datasets.
• Compare the performance of these models in terms of accuracy to determine which model better
distinguishes between the two penguin species. Provide a brief explanation of your findings.
2. AUC (Area Under the ROC Curve) Comparison:
• Calculate the AUC for both Naive Bayes and Logistic Regression on the training and test datasets.
• Interpret the AUC values for both models to assess how effectively each model discriminates between
the two penguin species.
• Provide insights into which model is more effective based on the AUC metric.
3. Lift and Gain Charts:
• Generate Lift and Gain charts for both Naive Bayes and Logistic Regression using 10 deciles.
• Use a dual y-axis plot with deciles on the x-axis, and Lift and Gain on the y-axis.
• Evaluate the Lift and Gain charts to understand how well each model ranks the predicted probabilities
and how effective each model is in prioritizing the classification of the two species.
4. Model Performance Comparison:
• Based on the results from accuracy, AUC, and Lift/Gain charts, compare the overall performance of
Naive Bayes and Logistic Regression models.
• Discuss which model performs better in classifying the two penguin species and provide reasons for
your conclusion.
1
5. Performance on a Complex Dataset:
• Extend your analysis by applying both Naive Bayes and Logistic Regression to a more complex dataset,
such as MNIST (handwritten digits).
• Compare how the performance of generative models (e.g., Naive Bayes) and discriminative models
(e.g., Logistic Regression) differs when dealing with image data (MNIST) compared to the two-species
penguin dataset.
• Discuss the differences in performance and behavior across these datasets.

DS552 - Generative AI
Assignment-3
==========================

Task 1: Modify the VAE architecture to use convolutional layers for both the encoder and decoder, and
train it on the CIFAR-10 dataset. This modification will allow the model to capture spatial relationships
within images more effectively, improving its ability to generate high-quality images. After training, compare
the generated images with those from a fully connected VAE.
Task 2: Using the trained VAE, interpolate between two images in the latent space and generate intermediate
images. This demonstrates how smoothly the model can transition between different data points. Visualize
and display the results, showing the interpolated images in a grid format to observe the transformation.
Task 3: Train the VAE on a new dataset of your choice (e.g., CelebA for faces), and visualize generated
samples. Experiment with sampling from different regions of the latent space and analyze how the generated
outputs vary based on different latent vectors.
Coding Task Explanation: In this assignment, the VAE will be expanded by incorporating convolutional
layers in both the encoder and decoder networks. Convolutional layers are particularly effective for image
data, as they can capture spatial hierarchies better than fully connected layers. By using this architecture
on the CIFAR-10 dataset (a dataset of small, colorful images), the VAE will be able to learn a more effective
latent representation, which should improve the quality of generated images.
The second task involves interpolation in the latent space. By interpolating between two points in the latent
space (corresponding to two different images), we can observe how smoothly the VAE transitions between two
images. This task highlights the structure of the learned latent space and shows the generative capabilities
of the VAE.
Finally, applying the VAE to a new dataset (such as CelebA, a dataset of celebrity faces) and visualizing
the generated images allows us to see how well the model generalizes to different kinds of data and how the
latent space is structured for more complex, real-world images.

