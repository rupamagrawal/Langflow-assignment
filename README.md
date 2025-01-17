# Social Media Performance Analysis

An analytics module leveraging LangFlow and DataStax Astra DB to provide insights into social media performance. This project uses a mock dataset to demonstrate how workflows created with LangFlow can be integrated for seamless and robust data analysis.

Tools used and their Features:
● LangFlow-Powered Insights: Easily generate insights through a LangFlow-generated API workflow.

● DataStax Astra DB: Leverages a distributed cloud database for reliable data storage and processing.

● Streamlit for frontend access of Langflow.

● API Integration: Communicates with LangFlow's REST API for real-time data analysis.

● Customizable: Configure endpoints and workflows based on project needs.



## Features

- Powered by **LangFlow** and **DataStax** for robust and accurate analysis.
- Interactive chat interface for social media performance analysis.
- Persistent query and response history using Streamlit's `session_state`.
- Easy-to-use interface with real-time insights from LangFlow.

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Aryan-Jadhav3009/Langflow-Assignment
cd Langflow-Assignment
```

### 2. Create a Virtual Environment
Set up a Python virtual environment to manage dependencies:
```bash
python -m venv env

```
Activate the virtual environment:
On Windows:
```bash
source env/Scripts/activate
```
On Mac/Linux:
```bash
source env/bin/activate
```

### 3. Install Dependencies
Install the required Python libraries:

```bash
pip install -r requirements.txt
```
### 4. Create a .env File
Create a .env file in the root directory of your project and add the following:

dotenv
```
APP_TOKEN=<your-langflow-generated-token>
```
Replace <your-langflow-generated-token> with the API token generated by LangFlow.

### 5. Run the Application
Start the Streamlit application:

```bash
streamlit run main.py
```
🚀 Deploy Link
Access the live application here: https://langflow-assignment-jfpfpajnd2wfpavvvaowzp.streamlit.app/ 
## How to Use
(1) Enter your query in the text area provided.

(2) Click on the "Generate Insights" button to analyze the query.

View the analysis result along with the chat history displayed below the input area.

## Project Structure
- main.py: Main application file containing the Streamlit app logic.
- requirements.txt: List of dependencies required for the project.
- .env: File for storing environment variables securely.

## Demonstration
https://www.youtube.com/watch?v=4S4yKrse48I&t=12s&ab_channel=Passionatebread

## Notes
Ensure you have a valid LangFlow APP_TOKEN before running the application.

The API token is stored securely in the .env file and accessed through python-dotenv.
