# GAT Website Project README

Welcome to the README file for the GAT (Generic Administration Tool) Website project! This project is designed to provide a web-based platform for teachers and students to manage various details related to the R&D department of the college. The website allows users to perform CRUD (Create, Read, Update, Delete) operations on different categories of data, such as conference papers, journals, patents, book chapters, PhD scholars, consultancy projects, funded projects, and workshops. The project is built using the Flask framework and utilizes the XAMPP server along with MySQL to store data in a database.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The GAT Website project is aimed at providing an efficient and user-friendly platform for teachers and students to manage and maintain various research and development details within the college's R&D department. By utilizing the Flask framework and MySQL database, the project offers a robust and responsive solution to handle CRUD operations on different categories of data, ensuring ease of use and data integrity.

## Features

The GAT Website project comes with the following features:

- **User Authentication**: Teachers and students can log in to the website using their respective credentials.
  
- **CRUD Operations**: Users can perform Create, Read, Update, and Delete operations on the following types of data:
  - Conference Papers
  - Journals
  - Patents
  - Book Chapters
  - PhD Scholars
  - Consultancy Projects
  - Funded Projects
  - Workshops
  
- **Dashboard**: Users are presented with a personalized dashboard that provides an overview of their submitted and managed items.
  
- **Search and Filters**: Users can search and filter data based on different criteria, making it easy to locate specific items.
  
- **Data Validation**: The system enforces data validation to ensure that accurate and valid information is stored in the database.
  
- **Responsive Design**: The website is designed to be responsive, ensuring a seamless user experience across various devices.

## Installation

To set up the GAT Website project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gat-website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd gat-website
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the MySQL database using XAMPP or any other MySQL server setup.

5. Configure the database connection in the `config.py` file.

6. Run the Flask application:
   ```bash
   python app.py
   ```

7. Access the website in your web browser at `http://localhost:5000`.

## Usage

1. Launch the website using the provided URL.

2. Log in using your teacher or student credentials.

3. Navigate through the different sections to perform CRUD operations on various types of data.

4. Use the dashboard, search, and filter options to manage and access data efficiently.

## Contributing

We welcome contributions to the GAT Website project! If you want to contribute, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them with descriptive commit messages.

4. Push your changes to your forked repository.

5. Create a pull request to the main repository's `develop` branch, explaining your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to explore, use, and contribute to the GAT Website project. If you encounter any issues or have suggestions, please create an issue on the repository. Happy coding! 🚀
