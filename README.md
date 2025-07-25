This project analyzes internal employee messages to identify sentiment trends, highlight risks, and build predictive models for HR insights.


## Project Structure

employee_sentiment_analysis/
│
├── data/
│ ├── raw/ # Original test.csv
│ └── processed/ # Cleaned & labeled data files
├── main.ipynb ## **The main file where all the processes are done**<-- run this
├── notebooks/ # One notebook per task(used for testing purposes)
├── visualization/ # Plots and charts
├── report.docx # final report summary
├── README.md
└── requirements.txt 

From the monthly rankings of the employees, the overall top three positive employees are:
 lydia.delgado@enron.com, john.arnold@enron.com, eric.bass@enron.com. 
The top three negative employees are:
 rhonda.denton@enron.com, johnny.palmer@enron.com, bobette.riner@ipgdirect.com

The flight risks are identified by an employee who has sent 4 or more negative emails in a span of 30 days. They are:
bobette.riner@ipgdirect.com,
john.arnold@enron.com,
johnny.palmer@enron.com,
lydia.delgado@enron.com,
patti.thompson@enron.com,
rhonda.denton@enron.com,
sally.beck@enron.com

Key Insights
- Most employees show stable sentiment month-to-month
- A small number of employees account for a large share of negative messages
- Text length and frequency correlate modestly with sentiment

## Install dependencies using:

```bash
pip install -r requirements.txt