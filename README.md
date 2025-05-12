# 🧠 Automated Blog Generator using CrewAI

This project simulates a team of AI agents working together to generate a complete blog post—from research to editing—using the [CrewAI](https://github.com/joaomdmoura/crewAI) framework and the DuckDuckGo API.

## 🚀 Features

- **DuckDuckGoAgent**: Gathers real-time data on any topic using the DuckDuckGo API.
- **Planner Agent**: Creates a detailed content outline, including SEO and audience analysis.
- **Writer Agent**: Crafts a blog post based on the planner's outline.
- **Editor Agent**: Proofreads and polishes the final post for tone and clarity.
- **Sequential Task Execution**: Tasks are run in a logical sequence: plan → write → edit.

## 🧩 Tech Stack

- Python
- CrewAI
- DuckDuckGo Instant Answer API
- OpenAI (for agent capabilities)

## 🛠️ How to Run

1. Install dependencies:
   ```bash
   pip install crewai requests
Add your OpenAI API Key:

python
Copy
Edit
os.environ['OPENAI_API_KEY'] = 'your_api_key'
Run the script (Jupyter Notebook or convert to .py):

bash
Copy
Edit
python your_script.py
📝 Sample Input
python
Copy
Edit
crew.kickoff(inputs={"topic": "What do you know about F1 cars?"})
📄 Output
A fully-written and edited blog post in Markdown format, ready for publication.

📚 References
CrewAI on GitHub

DuckDuckGo API

License: MIT
Author: Yasir Azam
