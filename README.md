# Titanic_Dataset
This project analyzes the Titanic passenger dataset to uncover survival patterns based on features like age, sex, and passenger class.

📁 Project Structure
Titanic.ipynb / Titanic (1).ipynb — Jupyter Notebooks for data cleaning, exploration, and visualization.

train_and_test2.csv — The Titanic dataset used for analysis.

Titanic_Analysis_Report.pdf — A complete PDF report summarizing the findings with graphs and key insights.

🛠 How to Run Locally
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/titanic-analysis.git
cd titanic-analysis
Install required libraries:

Make sure you have Python installed (preferably 3.8+).
Install necessary packages using:

bash
Copy
Edit
pip install pandas matplotlib seaborn fpdf
Run the Notebook:

Open Jupyter Notebook or VSCode and run:

bash
Copy
Edit
jupyter notebook Titanic.ipynb
Generate PDF Report (Optional):

The notebook includes code to generate a Titanic_Analysis_Report.pdf file automatically using fpdf.

📊 Key Findings
Most passengers were aged between 20 and 40 years.

Women had a much higher survival rate than men.

First-class passengers had better survival chances compared to second and third classes.

Fare distributions were heavily right-skewed with few high-paying passengers.

📎 Notes
Some columns (zero, zero.1, etc.) were dropped during cleaning.

The original '2urvived' column was renamed to 'Survived'.

Missing values in Age were handled by ignoring during initial plots.

🧠 Future Improvements
Handle missing values properly (e.g., imputing missing Age).

Build a simple machine learning model to predict survival.

Deploy an interactive dashboard (e.g., with Streamlit or Dash).

📜 License
This project is licensed under the MIT License.

✏️ Feel free to fork, improve, or use it for your own Titanic projects!

