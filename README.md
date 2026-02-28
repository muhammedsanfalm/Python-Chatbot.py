# Python-Chatbot.py

import nltk
from nltk.tokenize import word_tokenize

# Run once
# nltk.download('punkt')

print("Chatbot: Hello! Type 'bye' to exit.")

while True:
    user_input = input("You: ").lower()

    if 'bye' in user_input:
        print("Chatbot: Goodbye 👋")
        break

    

    elif 'how are you' in user_input:
        print("Chatbot: I'm doing great 😊")

    elif 'thank' in user_input:
        print("Chatbot: You're welcome!")

    elif 'what is machine learning' in user_input :
        print("Chatbot: Machine learning is a branch of AI that allows systems to learn from data and improve automatically.")

    elif 'types' in user_input:
        print("Chatbot: The main types are supervised, unsupervised, and reinforcement learning.")

    elif 'supervised' in user_input:
        print("Chatbot: Supervised learning uses labeled data to train models. Example: classification.")

    elif 'unsupervised' in user_input:
        print("Chatbot: Unsupervised learning finds patterns in unlabeled data. Example: clustering.")

    elif 'reinforcement' in user_input:
        print("Chatbot: Reinforcement learning learns through rewards and penalties. Example: game AI.")

    elif 'algorithm' in user_input:
        print("Chatbot: Common ML algorithms include Linear Regression, Decision Tree, KNN, and SVM.")

    elif 'dataset' in user_input or 'data' in user_input:
        print("Chatbot: A dataset is a collection of data used to train and test machine learning models.")

    elif 'model' in user_input:
        print("Chatbot: A model is a trained program that makes predictions based on data.")

    elif 'training' in user_input:
        print("Chatbot: Training is the process of teaching a model using data.")

    elif 'testing' in user_input:
        print("Chatbot: Testing checks how well a trained model performs on new data.")

    elif 'hii' in user_input or 'hello' in user_input:
        print("Chatbot: Hello! How can I help you?")

    elif 'application' in user_input:
        print("Chatbot: Machine learning is used in recommendation systems, fraud detection, and image recognition.")

    else:
        print("Chatbot: Sorry, I didn't understand that.")
