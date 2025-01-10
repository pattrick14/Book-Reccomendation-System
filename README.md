# Book-Reccomendation-System

This project is a **Book Recommendation System** that suggests books to users based on their preferences

## Features

1. **Data Processing:** 
   - Reads and processes the data from `books.csv`, `ratings.csv`, and `users.csv` to build a recommendation model.
   - Uses collaborative filtering techniques for personalized recommendations.

2. **Model Creation:**
   - A Jupyter Notebook `recommendation_system.ipynb` processes the data and generates a `.pkl` file (`books.pkl`) for use in the Flask app.

3. **Web Application:**
   - Flask is used to create a simple web application.
   - Users can input preferences, and the app suggests books based on the trained model.

4. **Frontend Display:**
   - The `templates/` folder contains HTML templates for the homepage and results display.
  
### Prerequisites

- Python 3.x
- Flask
- Pandas
- Scikit-learn
- Jupyter Notebook

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/pattrick14/Book-Reccomendation-System.git
   cd Book-Reccomendation-System
2. Open the Jupyter Notebook to process data and create the model:

   ```bash
   jupyter notebook book-recommendation.ipynb

3. Run the app:
   ```bash
   cd Book-Recommendation-System
   flask run

# Screenshots
![image](https://github.com/user-attachments/assets/ebb5f789-f0aa-4217-a16e-4a3159a05f42)
![image](https://github.com/user-attachments/assets/623c95e4-c9ff-49a7-aa46-6e113595cf98)
![image](https://github.com/user-attachments/assets/b6293f08-40b5-4417-b00f-1835166c6c02)

