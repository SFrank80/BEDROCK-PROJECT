
README for Vanguard Stock Holdings Analysis Using Generative AI
Project Overview
This project utilizes advanced Generative AI tools, Amazon Bedrock and Claude 3, to analyze the Vanguard stock holdings for January and February. The aim is to identify significant changes in the share counts of the top 30 holdings, illustrating the application of AI in financial data analysis.

Technical Description
Amazon Bedrock: Provides the cloud environment for executing AI models securely and efficiently.
Claude 3: Analyzes textual data, extracting meaningful patterns and insights from structured financial datasets.
Files
jan_holdings.csv: Contains Vanguard's stock holdings data for January.
feb_holdings.csv: Contains Vanguard's stock holdings data for February.
finding.txt: Lists the top 30 holdings with the most significant changes in share counts, as determined by the analysis.
Data Preparation and Analysis Process
CSV Data Conversion:

Initially, the data from jan_holdings.csv and feb_holdings.csv is loaded using Python's CSV module. Each record from the CSV files is read and then transformed into a single formatted string. This transformation involves joining the fields of each record with vertical bars (|) and concatenating each line with a newline character to maintain readability and structure.
This string formatting is crucial for Claude 3 to process the information effectively, as the AI model requires data in a text-based format that simulates natural language.
AI Analysis:

The formatted string data for both January and February is passed to Claude 3 via the Bedrock platform. The analysis is driven by a custom configuration that instructs the model to compare the data and identify changes in the holdings between the two months.
Claude 3 processes this data, focusing on discerning the differences in share counts, and generates a detailed list of the top 30 holdings showing the most significant changes.
Output Generation:

The results from Claude 3 are compiled into finding.txt, which provides an enumerated list detailing the changes in share counts for the top 30 stocks. This file serves as a concise summary of the analysis, suitable for stakeholders interested in market trends and investment insights.
Results Summary
The analysis showcases notable changes in stock holdings, with detailed insights into the stocks that experienced the most significant fluctuations in their share counts. This project highlights the potential of Generative AI to transform financial analytics by providing faster and more accurate analysis of complex datasets.
