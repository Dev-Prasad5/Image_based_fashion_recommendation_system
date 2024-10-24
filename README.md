
# Image Based Fashion Recommendation System

A Machine Learning based web application which allow users to get image based recommendations. Implemented machine learning algorithm like K-NN, CNN and trained ML model with 44k image dataset. The system suggests 5 similar fashion products as similar as input image.


## Introduction
Clothing is a kind of symbol that represents people’s internal perceptions through their
outer appearance. It conveys information about their choices, faith, personality, profession,
social status, and attitude towards life. Clothing is believed to be a non-verbal way of
communicating and a major part of people’s outer appearance. Research on textual content,
such as posts and comments, emotion and information diffusion, and images has attracted
the attention of modern-day researchers, as it can help to predict fashion trends and facilitate
the development of effective recommendation systems. An effective recommendation system
is a crucial tool for successfully conducting an e-commerce business.
## Problem Definition
The problem definition for an image-based fashion recommendation system is to develop
a system that can accurately analyze and interpret images of clothing items or outfits to
provide personalized recommendations to users based on their visual preferences and style.
The system should be able to understand the user’s desired aesthetic, color schemes, patterns,
and overall style from the uploaded or searched images.
## Objective
Objective of this project is as follows:
- Personalized recommendations: The fashion recommendation system should provide personalized recommendations based on the user’s preferences.
- Visual search: The system should allow users to search for fashion items using images.
- Seamless integration with e-commerce platforms: The fashion recommendation system should seamlessly integrate with the e-commerce platform, allowing users to easily add recommended items to their shopping cart and make purchases.

## System Architecture
![System Architecture](https://github.com/user-attachments/assets/6f2b73d6-6ece-4df7-a1ed-ab14ba63c669)

## Training the Neural Networks

Once the data is pre-processed, the neural networks are trained, utilizing transfer learning from [ResNet50](https://blog.roboflow.com/what-is-resnet-50/). More additional layers are added in the last layers that replace the architecture and weights from ResNet50 in order to fine-tune the network model to serve the current issue. The figure shows the ResNet50 architecture.
## Dataset

 - [Kaggle Dataset (572 MB)](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)
## Demo
![output1](https://github.com/user-attachments/assets/22b98bef-019f-4aaf-8450-697e15b11ba1)
![output2](https://github.com/user-attachments/assets/9e8567b4-494b-4fbd-9651-a83214abb402)
![output3](https://github.com/user-attachments/assets/578e219b-c238-4d5f-89f7-08e89cc8111f)

## Dataset

 - [Kaggle Dataset (572 MB)](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)


## Conclusion

In conclusion, the implementation of an image-based fashion recommendation system can
significantly improve the shopping experience for users. By utilizing advanced image recognition and machine learning algorithms, 
this system can accurately analyze and understand user's style preferences based on their uploaded images. This allows for more precise and
personalized recommendations, ensuring that users are presented with clothing items that align with their individual tastes and preferences. Additionally, the image-based approach
eliminates the need for users to spend time searching and browsing through large catalogs, making the shopping process more efficient and convenient. Overall, the image-based fashion
recommendation system has the potential to revolutionize the fashion industry by offering a highly personalized and enjoyable shopping experience for users.

## Future scope

The future of image-based fashion recommendation systems is poised for exciting advancements.
With the integration of cutting-edge machine learning and deep learning techniques, these systems will offer increasingly personalized recommendations by analyzing user feedback, social media data, and real-time context. 
The future of image-based fashion recommendation systems promises to enhance personalization, creativity, and discovery for users worldwide.
