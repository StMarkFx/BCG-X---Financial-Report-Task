BCG-X - Financial Report Task

Introduction
This repository contains the code, data, and analysis conducted for the BCG-X Financial Report Task. The project focuses on manually extracting, analyzing, and interpreting key financial data from the 10-K filings of Microsoft, Tesla, and Apple for the last three fiscal years. The insights from this analysis will inform the development of an AI-powered financial chatbot.

Getting Started

Prerequisites
To run the analysis and explore the data, ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn

Installation
Clone the repository and navigate to the project directory:
git clone https://github.com/StMarkFx/BCG-X---Financial-Report-Task.git
cd BCG-X---Financial-Report-Task

Install the required Python packages:
pip install -r requirements.txt

Usage
To reproduce the analysis:
- Open the Jupyter Notebook (analysis.ipynb).
- Run the cells sequentially to perform the data analysis.
- Review the visualizations and findings presented in the notebook.


Project Objectives
The primary objectives of this project are:
- Manual Data Extraction: Extracting key financial figures from the 10-K filings of Microsoft, Tesla, and Apple for the fiscal years 2021, 2022, and 2023.
- Data Analysis: Analyzing trends in Total Revenue, Net Income, Total Assets, Total Liabilities, and Cash Flow from Operating Activities using Python.
- Insight Development: Providing actionable insights to inform the development of an AI-powered financial chatbot.
- Documentation: Documenting the methodology, analysis, and findings in a clear and concise manner using Jupyter Notebooks.


Data Extraction
Financial data was manually extracted from the SEC’s EDGAR database, focusing on the following metrics:
- Total Revenue
- Net Income
- Total Assets
- Total Liabilities
- Cash Flow from Operating Activities

Additionally, the following metrics were derived and analyzed:
- Earnings Per Share (EPS)
- Debt-to-Equity Ratio
- Year-over-Year Revenue Growth (%)
- Year-over-Year Net Income Growth (%)


Data Analysis
The analysis was performed using Python, with the key steps including:
- Loading and cleaning the extracted data.
- Calculating key financial metrics and trends.
- Creating visualizations to aid in the interpretation of the data.
- Summarizing findings and providing insights based on the analysis.


Key Metrics and Calculations:
- Year-over-Year Growth: Calculated for Total Revenue and Net Income to assess the growth trajectory of each company.
- Rolling Averages: Applied to smooth out fluctuations and identify longer-term trends.
- Correlation Analysis: Conducted to understand the relationships between different financial metrics.

Results and Findings
The results of the analysis provide a comprehensive view of the financial health and performance of Microsoft, Tesla, and Apple over the last three fiscal years. Key observations include
- Consistent revenue growth for all three companies, with Tesla experiencing the most significant surge in 2023.
- Strong net income growth across the board, with notable increases for Tesla.
- Stable EPS for Microsoft, with significant growth for Tesla and steady increases for Apple.
- Debt-to-Equity ratios reflecting varying levels of financial leverage, with Tesla showing more aggressive growth strategies.


Conclusion
The analysis highlights the robust financial performance of Microsoft, Tesla, and Apple, with Tesla standing out for its rapid expansion. These insights are critical for informing the development of an AI-powered financial chatbot that can provide users with accurate and meaningful financial advice.

Repository Structure
BCG-X---Financial-Report-Task/
│
├── !10-K Reports.xlsx        # Contains extracted financial data
├── analysis.ipynb            # Main Jupyter Notebook for the analysis
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation (this file)
└── Other CSVs                # Generated data from analysis


Contributing
Contributions to the project are welcome. If you have suggestions or improvements, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the BCG-X team for the opportunity to work on this financial analysis task and to the open-source community for the tools and libraries used in this project.
