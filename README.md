## AI/ML Model Training and Evaluation
### 1. Data Splitting
The first step in our process involved splitting the dataset into two parts: training data and testing data. This was accomplished using the splitfolders module, with an 80/20 ratio—80% of the data was allocated for training the model, and the remaining 20% was reserved for testing. This division ensures that the model has a robust dataset to learn from while also having sufficient data to validate its performance.

![Screenshot 2024-12-07 182657](https://github.com/user-attachments/assets/09b05b55-f4ad-4148-96a0-1287374e4e09)

### 2. Image Transformation
Subsequently, we transformed the images to the required size suitable for the pre-trained model parameters. This step is crucial as it ensures compatibility with the model’s input specifications, thereby enabling accurate and efficient processing of the data.

![Screenshot 2024-12-07 182705](https://github.com/user-attachments/assets/4b6f03c1-dddb-4c56-9a6f-c8d9dc5b44a4)

### 3. Model Configuration
In this phase, we customized the pre-trained model by turning off or "freezing" specific layers. By doing this, we retained the beneficial features of the pre-trained model while optimizing it for our specific task, ensuring that the model outputs the correct predictions for our data.

![Screenshot 2024-12-07 183125](https://github.com/user-attachments/assets/70376e39-8922-4701-9a10-e05f421ce362)

### 4. Model Training
We trained the model over the course of 10 epochs. An epoch involves a complete pass through the entire training dataset. During each epoch, the model adjusts its parameters to minimize prediction errors, effectively learning from the patterns in the data to accurately predict labels when shown new images.

![Screenshot 2024-12-07 183141](https://github.com/user-attachments/assets/7aba1c46-c581-4fda-b997-309f657231c4)

### 5. Performance Evaluation
After training, we evaluated the model’s performance by plotting the accuracy metrics for both the training and test datasets. These plots visually represent how well the model has learned to generalize from the training data to the unseen test data, which is critical in assessing the model’s effectiveness.

![Screenshot 2024-12-07 183149](https://github.com/user-attachments/assets/aedbcb8f-6822-4346-9916-40951046a698)

### 6. Model Testing with Random Images
Finally, we tested the model’s predictive capabilities by using random images from our dataset. This step involved feeding these new, unseen images into the model and observing whether it could correctly identify and predict the labels. This final validation step ensures the model’s practical applicability and robustness in real-world scenarios.

![Screenshot 2024-12-07 183205](https://github.com/user-attachments/assets/c7c46583-1560-4d80-991b-cdd37f4e975e)

 Despite time constraints and a rapidly approaching due date, I delved into object detection by experimenting with various codes. Although I was unable to fully validate the effectiveness of the approach, this initial exploration provided valuable insights and foundational knowledge that will undoubtedly inform future iterations and improvements

Feel Free to Connect me :- anithprakashan123@gmail.com



