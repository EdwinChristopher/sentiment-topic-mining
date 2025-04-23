Preproses data, smote(data balancing), building model(for guessing sentiment on tweet), use that model to labeling new dataset, after that i want to make a supervised model using randomForest to guess the topic on every text on every label on the new dataset. so we need to define te main topic, so i use spaCy model to get top 10 topic from data(preproses needed). with that 10 topics now i can use fast text model to get the similarity from every data to that 10 topics. After we get the similarity of 10 topics, i train model using randomForest to that 10 topics, so i can get 10 models for every topic. after that we use that 10 randomForest model to labeling the new data wether it contains that topic or not. after that we get the main result, the topics from positive, negative, and neutral sentiment. 
![image](https://github.com/user-attachments/assets/50f4faee-a055-4cb3-8ea5-f0000ae8b7f6)
![image](https://github.com/user-attachments/assets/024bef06-8c00-4bfc-a909-ae9648ad5b52)
![image](https://github.com/user-attachments/assets/b7a05898-37e1-440f-9ac9-d4ef6bb16186)
![image](https://github.com/user-attachments/assets/1d6802f2-9b7c-4232-8aa7-c6bc7f1e2c5c)
![image](https://github.com/user-attachments/assets/96bff193-5067-4bf1-82a4-8af1859d2cb7)
![image](https://github.com/user-attachments/assets/b0df13d5-47d9-4585-b03b-4ef853f0f698)
