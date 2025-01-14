## AI/ML Model Training and Evaluation
### 1. Data Splitting
The first step in our process involved splitting the dataset into two parts: training data and testing data. This was accomplished using the splitfolders module, with an 80/20 ratio—80% of the data was allocated for training the model, and the remaining 20% was reserved for testing. This division ensures that the model has a robust dataset to learn from while also having sufficient data to validate its performance.

![Screenshot 2024-12-07 182657](https://github.com/user-attachments/assets/4962cff5-8f9d-446e-aa1b-ffb88b21f607)

### 2. Image Transformation
Subsequently, we transformed the images to the required size suitable for the pre-trained model parameters. This step is crucial as it ensures compatibility with the model’s input specifications, thereby enabling accurate and efficient processing of the data.

![Screenshot 2024-12-07 182705](https://github.com/user-attachments/assets/fb5d669e-2b87-4eba-9273-1c897da0b189)

### 3. Model Configuration
In this phase, we customized the pre-trained model by turning off or "freezing" specific layers. By doing this, we retained the beneficial features of the pre-trained model while optimizing it for our specific task, ensuring that the model outputs the correct predictions for our data.

![Screenshot 2024-12-07 183112](https://github.com/user-attachments/assets/50d5cc3c-fe1b-4980-a5ca-a34ce40f8737)

### 4. Model Training
We trained the model over the course of 10 epochs. An epoch involves a complete pass through the entire training dataset. During each epoch, the model adjusts its parameters to minimize prediction errors, effectively learning from the patterns in the data to accurately predict labels when shown new images.

![Screenshot 2024-12-07 183125](https://github.com/user-attachments/assets/50a5fc47-f0b1-4b30-9af5-94125642c28d)

### 5. Performance Evaluation
After training, we evaluated the model’s performance by plotting the accuracy metrics for both the training and test datasets. These plots visually represent how well the model has learned to generalize from the training data to the unseen test data, which is critical in assessing the model’s effectiveness.

![Screenshot 2024-12-07 183141](https://github.com/user-attachments/assets/63f1c9be-c31e-4d5b-915d-637ba6bad935)

### 6. Model Testing with Random Images
Finally, we tested the model’s predictive capabilities by using random images from our dataset. This step involved feeding these new, unseen images into the model and observing whether it could correctly identify and predict the labels. This final validation step ensures the model’s practical applicability and robustness in real-world scenarios.

![Screenshot 2024-12-07 183205](https://github.com/user-attachments/assets/c7c46583-1560-4d80-991b-cdd37f4e975e)

 Despite time constraints and a rapidly approaching due date, I delved into object detection by experimenting with various codes. Although I was unable to fully validate the effectiveness of the approach, this initial exploration provided valuable insights and foundational knowledge that will undoubtedly inform future iterations and improvements

Feel Free to Connect me :- anithprakashan123@gmail.com



