# Spending Insights Advisor with LLM

## Overview
This project, titled "Spending Insights Advisor with LLM," explores the integration of Large Language Models (LLMs) with SQL databases to provide actionable insights from raw transactional data. The project leverages LangChain, an open-source Python library, for seamless communication between the LLM and the SQLite database. Through prompt engineering techniques, the capabilities of LLMs are enhanced to interpret natural language queries and retrieve relevant information from the database.

## Key Learnings
- Established a robust system connecting SQLite database and LLM via LangChain, facilitating the transformation of raw data into actionable insights.
- Enhanced LLM capabilities through prompt engineering, enabling seamless integration with SQL databases.
- Developed a Flask app to manage user queries and deliver insightful responses.

## AI Model
The project utilizes the LLAMA_2_70B_CHAT model on IBM Watsonx, IBM's cloud service platform, to translate user questions into SQL queries and subsequently into results.

## Acknowledgment
A heartfelt thanks to IBM IBMSkillsNetwork for their invaluable guidance and expertise throughout the project, which significantly contributed to its success.

## Setting Up
To set up the project environment:
1. Install virtualenv: `pip3 install virtualenv`
2. Create a virtual environment: `virtualenv my_env`
3. Activate the virtual environment: `source my_env/bin/activate`
4. Clone the project repository: `git clone https://github.com/ibm-developer-skills-network/TransactBot`
5. Navigate to the project directory: `cd TransactBot`
6. Install project requirements: `pip3 install -r requirements.txt`

## Understanding the Front-End
The project's front-end interface comprises:
- **index.html**: Skeleton of the website containing elements like buttons and text boxes.
- **style.css**: Adds styles, colors, and animations to enhance the website's appearance.
- **script.js**: Enables interactive functionalities such as theme changes and message sending.

## Interacting with the Database
The Flask app's `/inquiry` route handles incoming queries to retrieve data from the SQLite database. User prompts are merged with prompt templates, facilitating seamless interaction with the database.

## Prompting the Database
To initialize the database chain, LangChain's SQLDatabaseChain library is utilized, bridging the SQLite database with the LLM.

## Conclusion
The "Spending Insights Advisor with LLM" project showcases the power of integrating natural language processing with database management to extract actionable insights from transactional data. By combining LangChain, LLMs, and SQL databases, this project demonstrates a novel approach to data analysis and decision-making.
