# NASA APOD Data Retrieval - Small API Exercise

This is a small exercise focusing on handling APIs using Python. 
The project involves retrieving data from the **NASA Astronomy Picture of the Day (APOD) API**, processing it, and storing the results in a JSON file.

---

### Key Features:
- **API Handling:** Uses the NASA APOD API to fetch daily astronomy pictures and their descriptions.
- **Data Processing:** Retrieves APOD data for a range of dates and stores it in a structured JSON format.
- **File Operations:** Reads, processes, and summarizes the stored data, extracting useful insights.
- **Error Handling:** Implements exception handling for API calls and file operations.

---

## Setup Instructions

### 1. Access the Project Files
-  Clone the Repository 

---

### 2. Create and Activate a Virtual Environment (Optional)
```bash
python -m venv venv
source venv/bin/activate  
# On Windows: 
source venv\Scripts\activate
```

---

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

### 4. Set Up the API Key
- This project includes an api.env file for convenience.
- The file contains the following pre-configured API key for submission:
  ```plaintext
  API_KEY = 'AdyflA9fKwyKTOn48E9WqUWKxuEPl87YQ8DQ7tWW'
  ```
- **Important**: The pre-configured API key will be removed after project evaluation. 
- To use the project beyond submission, obtain your own API key from [NASA's API Portal](https://api.nasa.gov/) and replace the key in the `api.env` file.

---

### 5. Run the Project
- Start Jupyter Notebook by running:
```bash
jupyter notebook
```

- Alternatively, click the "Run" button in your IDE.

---

## Notes
- The `api.env` file is included for testing purposes with a valid API key. Replace the key for personal or future use.

---

## Dependencies
The project requires the following Python libraries:
- `requests`
- `python-dotenv`
- `jupyter`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

These are listed in the requirements.txt file for easy installation.



