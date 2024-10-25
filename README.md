# Chat with MySQL - AI-Powered SQL Query Generator

This Streamlit-based application allows users to chat with a MySQL database and interact with it using natural language. The app is powered by an AI model that interprets user queries, generates corresponding SQL queries, and returns the results in a conversational format.

![App Screenshot](path-to-your-screenshot.png)

## Features

- **AI-powered SQL query generation:** Interact with the database using natural language queries.
- **Supports custom MySQL databases:** Users can upload their own `.sql` files to connect and query their database.
- **Conversational Responses:** The app returns SQL query results in easy-to-understand conversational text.
- **Streamlit Interface:** Intuitive user interface for entering database credentials, uploading files, and viewing query results.

## How It Works

1. **User Input:** Type a question or query in natural language (e.g., *"Show me the top 5 customers by purchase amount."*).
2. **SQL Query Generation:** The app uses an AI model to generate the SQL query based on the database schema and user input.
3. **Response:** The SQL query is executed, and the results are displayed in a conversational format.

## Demo

You can try the demo app [here](https://example-demo-link.com).

## Getting Started

### Prerequisites

- Python 3.8 or higher
- [Streamlit](https://docs.streamlit.io/library/get-started/installation) installed
- A MySQL database or `.sql` file to upload

### Installation

1. **Clone the Repository:**

```bash
git clone https://github.com/SahiLmb/Multi-AI-SQL.git
cd AI MYSQL DB/src
```

2. **Install Dependencies:**

```bash
pip install -r requirements.txt
```

3. **Set Up Environment Variables:**

Create a `.env` file in the root directory and add your Groq API key:

```env
GROQ_API_KEY=your-groq-api-key
```

4. **Run the Application:**

```bash
streamlit run app.py
```

5. **Access the App:**

Go to `http://localhost:8501` in your browser to access the app.

### File Upload

You can upload a `.sql` file containing your database schema. The app will temporarily store the file and use it for generating SQL queries.

### Example Usage

- **Query:** *"Show me the top 10 employees by salary."*
- **Generated SQL:** `SELECT EmployeeID, Salary FROM Employees ORDER BY Salary DESC LIMIT 10;`
- **Response:** "Here are the top 10 employees by salary..."

## Technologies Used

- **[Streamlit](https://streamlit.io/)** - Frontend framework
- **[GroqCloud]((https://console.groq.com/playground)/)** - GPT model for natural language processing
- **[SQLAlchemy](https://www.sqlalchemy.org/)** - Database interaction
- **[MySQL](https://www.mysql.com/)** - Backend database

## Contributing

Feel free to fork this repository, create a new branch, and submit a pull request. All contributions are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, feel free to contact me:

- **GitHub:** [SahiLmb](https://github.com/SahiLmb)
---

