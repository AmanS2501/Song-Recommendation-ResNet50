Song Recommendation System Based on Image Input

This project is a Song Recommendation System that suggests songs to users based on the landscape detected from the image input. The system leverages ResNet-50, a pretrained convolutional neural network model, to extract image features and map them to relevant music genres or moods.

Overview:

The system follows these steps:

1. Image Input: User provides an image as input.

2. Feature Extraction: The image is processed through the ResNet-50 model to extract landscape-related features.

3. Mapping Features to Music Genres: The extracted features are mapped to appropriate music genres or moods (e.g., calm, upbeat, melancholic).

4. Song Recommendation: Using clustering techniques like KNN or cosine similarity, the best-matching songs are fetched via the Spotify API or from a custom dataset.

Dataset:

The dataset used for training contains landscape images categorized into different natural terrains such as:

a. Forest

b. Desert

c. Glacier

d. Mountain

e. Beach

Technology Stack:

1. Python

2. PyTorch

3. ResNet-50 (Pretrained Model)

4. Spotify API

5. KNN / Cosine Similarity for Recommendation

Model Training:

The model was trained for 20 epochs with the following results:

a. Final Loss: 0.058

b. Validation Accuracy: 78.60%

Results:

Example feature extraction output:

1. Input Image: Glacier

2. Predicted Label: Glacier

Future Scope:

1. Improve accuracy using more advanced deep learning architectures.

2. Add support for more landscape categories.

3. Integrate more music streaming services.

Contribution:

Feel free to contribute to this project by creating a pull request.

Contact:

For any queries, contact Aman Shaikh at LinkedIn.