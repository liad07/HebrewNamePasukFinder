בס"ד
# Hebrew Name Pasuk Finder

סגולה שלא ישכח שמו ליום הדין: יאמר קודם יהיו לרצון השני בתפילת העמידה פסוק מהתנ"ך המתחיל באות הראשונה של שמו ומסתיים באות האחרונה של שמו .

## Description

Tanakh Name Verse Finder is a Python script that allows you to find verses from the Tanakh (Hebrew Bible) based on the first and last letters of a given name. This project uses a Microsoft Access database containing Tanakh verses for the lookup process.

## Features

- **Name-based Search:** Input a name, and the script will retrieve verses starting with the first letter and ending with the last letter of the name.

- **Database Connection:** Utilizes the `pyodbc` library to connect to the Tanakh database.

- **Error Handling:** Includes error handling to ensure a smooth user experience.

## Getting Started

### Prerequisites

- Python installed on your system.
- Microsoft Access Driver installed (for the Tanakh database).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Tanakh-Name-Verse-Finder.git
   ```

2. Install required Python packages:
   ```bash
   pip install pyodbc
   ```

### Usage

1. Run the script:
   ```bash
   python find_verse_by_name.py
   ```

2. Enter a name when prompted.

3. View the retrieved Tanakh verses based on the name.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your suggested enhancements.

