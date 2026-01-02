# The-Azure-Effect
Measuring the Jump in Clean Energy Production in Regions That Host Microsoft's Data Centers

In our statistical analysis we explore the effect of clean energy production in Business Authorities (BA’s) that host data centers between US power companies. We specifically compared the average clean energy output (in MW) in BA’s that host Microsoft Azure Data Centers and those that don’t.

Research Question:
Is the mean of clean energy generated higher for Balancing Authorities (BAs) that host known Microsoft Azure Data Centers compared to BAs that do not?

Null and Alternative Hypotheses
Null Hypothesis (H₀): There is no difference in the average clean energy output for power regions with Microsoft Azure Data Centers compared to those without.

Alternative Hypothesis (H₁): The average clean energy output for power regions (BAs) with Microsoft Azure Data Centers is higher compared to those without.

Python Version
Tested on: Python 3.11

Project Structure
├── Statistical_analysis.py # Python code file ├── README.md # Project documentation ├── requirements.txt # Dependencies file |── License # Copyright

Getting Started
How to run locally
Clone the Repository git clone https://github.com/SharmilNK/The-Azure-Effect.git
cd AIPI510_Project2

Create a virtual environment (optional but recommended):
python -m venv .venv source .venv/bin/activate # macOS/Linux .venv\Scripts\activate # Windows

Install Dependencies pip install -r requirements.txt
