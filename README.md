# 🥗 Diet Recommendation System

A content-based recommendation system built with Python to suggest personalized meals (breakfast, lunch, dinner, snacks) based on user profile inputs like age, weight, activity level, and dietary preferences.

## 📁 Files Included

* `diet_recommendation_model.ipynb`: Jupyter Notebook containing the code.
* `Food_and_Nutrition__.csv`: Dataset with meal plans and nutritional info.
* `diet_recommendation_model.pkl`: Pickled model for reuse.
* `requirements.txt`: Required Python libraries.

## 🔧 How It Works

The model:
* Takes in user inputs like age, weight, activity level, and dietary preferences.
* Encodes and normalizes the data.
* Uses **cosine similarity** to recommend the most relevant meals.

## 🧑‍💻 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/kananmahajan/diet-recommendation-system.git
   cd diet-recommendation-system
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook diet_recommendation_model.ipynb
   ```

4. Run the notebook to get personalized meal recommendations!

## 📊 Example Output

* **Breakfast**: Oatmeal with berries and nuts
* **Lunch**: Chicken breast with roasted vegetables
* **Dinner**: Steak with mashed potatoes and green beans
* **Snack**: Greek yogurt with berries

## 🛠️ Requirements

* pandas
* scikit-learn
* notebook

To install:
```bash
pip install -r requirements.txt
```
