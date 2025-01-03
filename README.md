# Project CS50 Search

## Overview
Project CS50 Search is a web-based application developed as part of the Harvard University CS50 course. This project implements a search engine where users can enter a search query and get results from a dataset. The core of the project is to simulate how search engines work in terms of indexing and searching data. The project uses Python, JavaScript, HTML, and CSS to provide a user-friendly interface and efficient search functionality.

## Features
- **Search Functionality**: The main feature of the project is a search bar that takes user input and displays relevant results.
- **Data Retrieval**: The project retrieves information from a dataset, processes it, and matches the query to provide accurate results.
- **User Interface**: The project provides a simple and easy-to-navigate web interface.
- **Responsive Design**: The app is designed to be responsive, adapting to different screen sizes, ensuring a smooth user experience on desktops and mobile devices.

## Technologies Used
- **HTML**: Used for structuring the web page content.
- **CSS**: Styled the project to make the interface clean, modern, and user-friendly.
- **JavaScript**: Implemented functionality for handling user input and displaying search results dynamically.
- **Python**: Used for backend processing to handle queries and search data.
- **Flask**: A Python web framework used for creating the web application and routing user requests.
- **SQLite**: A lightweight database used to store and retrieve data for search queries.

## How It Works
1. **User Input**: The user enters a search query in the input field.
2. **Backend Search**: The input query is sent to the backend, where a Python script processes the search against a dataset stored in an SQLite database.
3. **Results Display**: Once the data is processed, the search results are returned and displayed on the webpage dynamically.

## Project Setup

### Prerequisites
- Python 3.x
- Flask
- SQLite

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/youssef2007css/Project-CS50-Search.git
    cd Project-CS50-Search
    ```

2. Install the required Python dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:
    ```bash
    python app.py
    ```

4. Open your browser and go to `http://127.0.0.1:5000` to access the project.

## Dataset
The search engine works with a dataset that is pre-loaded in the SQLite database. The dataset contains a list of items that the user can search through. This dataset can be easily modified to suit other use cases.

## How to Use
1. Enter a search term into the search bar on the homepage.
2. Click the "Search" button or press "Enter" on your keyboard.
3. View the list of results returned based on your query.
4. Refine your search by entering different terms and adjusting filters if needed.

## Future Enhancements
- **Advanced Search Filters**: Implement advanced filtering options for more refined search results.
- **Better Search Algorithms**: Improve the backend search functionality by integrating more advanced search algorithms such as full-text search or ranking results.
- **User Authentication**: Add a user authentication system to save user preferences and search history.
- **Data Expansion**: Expand the dataset to include more varied types of data, enabling the search engine to serve a broader range of applications.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository, create a new branch, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **CS50**: This project was part of the CS50 course, an introductory computer science course offered by Harvard University.
- **Flask Documentation**: For the Flask framework that powers the web application.
- **SQLite**: For the lightweight database system used to store data.
