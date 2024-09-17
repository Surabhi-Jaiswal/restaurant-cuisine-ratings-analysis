Restaurant Cuisine Ratings Analysis 🍽️

## Project Overview

This project performs a high-level **Exploratory Data Analysis (EDA)** on restaurant cuisine ratings. The dataset contains customer preferences for various cuisines based on multiple demographic factors like **gender, profession, marital status, budget**, and **alcohol consumption**. The goal is to uncover insights that can help restaurants understand customer behavior better and tailor their services accordingly.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)


## Dataset

The dataset contains information about customers' demographics and their cuisine preferences, including:

- **User ID**: Unique identifier for each customer.
- **Area Code**: Area code of customer residence.
- **Location**: City and area of customer residence.
- **Gender**: Gender of customer.
- **Year of Birth (YOB)**: Year customer was born.
- **Marital Status**: Whether the customer is married or single.
- **Activity**: Customer profession (student or professional).
- **Budget**: Amount customers are willing to spend in the restaurant.
- **Cuisines**: Cuisine preferred by the customer.
- **Alcohol**: Frequency of alcohol consumption.

### Data Source

The dataset was provided by [Anirudh Kalabande](https://github.com/anirudhk08) and is shared within the data science community.


## Key Insights

Some of the main questions explored in this project:

1. Cuisine Preferences by Gender: How do male and female customers differ in their cuisine choices?

2. Budget vs Cuisine: What relationship exists between the budget and the type of cuisine preferred?

3. Customer Ratings by Profession: Do students and professionals rate their dining experiences differently?

4. Alcohol and Food Ratings: How does alcohol consumption affect cuisine ratings and preferences?

5. Marital Status and Preferences: Is there a difference in cuisine preferences between married and single customers?


## Visualizations

This project uses a variety of data visualizations to make insights clearer and actionable:

- Cuisine Preferences by Gender: Bar chart showing the most liked cuisines by gender.

- Budget vs. Cuisine: Scatterplot showing the relationship between customer budget and their cuisine preference.

- Customer Ratings by Profession: Comparison of ratings by professionals and students.

- Alcohol Consumption and Cuisine Ratings: Pie chart of alcohol consumption and its effect on food ratings.

- Marital Status & Preferences: Visualizing how marital status impacts cuisine selection.


## Technologies Used

- Python: Main programming language used.
- pandas: For data manipulation and analysis.
- matplotlib: For creating static, animated, and interactive visualizations.
- seaborn: For statistical data visualization.
- plotly: For interactive data visualization.



## Installation and Setup

### Prerequisites

Make sure you have Python and the required libraries installed. You can install the libraries by running:

```bash
pip install pandas matplotlib seaborn plotly
```

### Clone the Repository

To run this project locally, clone the repository:

```bash
git clone https://github.com/your-username/restaurant-cuisine-ratings.git
```

Navigate to the project directory:

```bash
cd restaurant-cuisine-ratings
```

---

## Usage

After installing the required libraries and cloning the repository:

1. Open the Jupyter Notebook or Python script.
2. Run the cells to perform the EDA on the dataset and generate visualizations.
3. You can modify the code to explore other relationships or customize the analysis further.

---

## Results

### Cuisine Preferences by Gender
![Cuisine by Gender](images/cuisine_by_gender.png)

### Budget vs. Cuisine Preference
![Budget vs. Cuisine](images/budget_vs_cuisine.png)

### Alcohol Consumption vs Cuisine Ratings
![Alcohol Impact](images/alcohol_impact.png)

These are just a few of the visualizations generated. You can view the full analysis in the provided notebooks.

---

## Contributing

Feel free to contribute to this project by opening a pull request or submitting issues for any bugs or feature requests. You can also suggest improvements or additional insights to explore.

### How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make the necessary changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Open a pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for exploring the world of data with me! Feel free to connect on [LinkedIn](https://www.linkedin.com/in/surabhi-jaiswal)!
