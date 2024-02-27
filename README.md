*Diet Recommendation System* 🥗📊
##Diet Recommendation System 
Welcome to the Diet Recommendation System, a web application designed to help you achieve a healthier lifestyle through personalized diet recommendations! Whether you're looking to maintain a balanced diet, address specific nutritional needs, or explore new and nutritious food options, this application has got you covered.

## :bookmark_tabs: Table of Contents
* [General Info](#general-info)
* [Development](#development)
* [Technologies](#technologies)
* [Setup](#setup)

## :scroll: General Info
### Motivation
In today's fast-paced world, maintaining a healthy lifestyle is crucial, and diet plays a significant role. This project aims to fill the gap in food/diet recommendation systems by using a content-based approach. It considers factors such as height, weight, and age to provide personalized recommendations, promoting a balanced and nutritious diet.

### What is a Food Recommendation Engine?
This recommendation engine utilizes a content-based approach, considering the nutritional content and ingredients of foods. It tailors recommendations based on individual dietary restrictions and preferences, offering users a guide to making healthier food choices and improving overall well-being.

### Content-Based Recommendation Engine
This system analyzes the characteristics or content of food items to recommend similar ones to users. By understanding patterns and features associated with specific items, it ensures relevant and transparent recommendations, making it user-friendly and effective.

### Why Content-Based Approach?
- No need for data from other users to start recommendations.
- Highly relevant and transparent recommendations.
- Avoids the "cold start" problem.
- Generally easier to create.

### Challenges
While content-based approaches have advantages, challenges include a potential lack of novelty and diversity, scalability issues, and the possibility of incorrect or inconsistent attributes.

## :computer: Development
### Model Development
The recommendation engine employs the Nearest Neighbors algorithm, an unsupervised learner for neighbor searches. Using the brute-force algorithm with cosine similarity, it ensures fast computation for small datasets.

### Dataset
The project utilizes the Food.com Kaggle dataset, comprising over 500,000 recipes and 1,400,000 reviews. [Explore the dataset here](https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews?select=recipes.csv).

### Backend Development
Built on the FastAPI framework, the backend efficiently handles user requests, utilizing the model to generate personalized food recommendations.

### Frontend Development
Streamlit is used for the user-friendly front-end, allowing easy navigation through the Hello page, automatic diet recommendation page, and custom food recommendation page.

### Deployment using Docker
Docker ensures a consistent environment, preventing unexpected issues, and simplifying scaling and management for larger machine learning projects.

### Project Architecture
![Architecture Diagram](Assets/Architecture_diagram.png)

## :rocket: Technologies
- Python 3.10.8
- FastAPI 0.88.0
- scikit-learn 1.1.3
- Pandas 1.5.1
- Streamlit 1.16.0
- Docker

## :whale: Setup

### Run Locally
1. Clone the repo:
   ```bash
   $ git clone https://github.com/zakaria-narjis/Diet-Recommendation-System
   ```

2. Run with Docker Compose:
   ```bash
   $ docker-compose up -d --build
   ```

3. Open [http://localhost:8501](http://localhost:8501) and enjoy the application! 😊

### Hosted Version
Explore the hosted version on [Streamlit Cloud](https://diet-recommendation-system.streamlit.app/).

Feel free to share your feedback and enjoy your journey to a healthier lifestyle with our Diet Recommendation System! 🌱🏋️‍♀️
