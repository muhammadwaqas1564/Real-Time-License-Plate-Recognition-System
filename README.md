# Real Time License Plate Recognition System 🚘🚔

A robust web-based application designed to recognize license plates from uploaded images, store detected data, and manage toll charges. The **License Plate Recognition System** uses computer vision to identify license plates and provides an intuitive dashboard for tracking vehicles and revenue.


## Features

- **Image Upload**: Upload images containing license plates for recognition.
- **License Plate Detection**: Automatically detects and extracts license plate text and confidence level.

## Future features 😎
- **Dashboard**: Track key metrics like total vehicles, revenue, and apply month-wise filters.
- **User Authentication**: Secure login for access to restricted sections.
- **Data Visualization**: View car entry trends and revenue statistics via interactive charts.


## Installation

1. **Clone the Repository**
    git clone https://github.com/your-username/license-plate-recognition-system.git
    cd license-plate-recognition-system
 

2. **Set up the Virtual Environment**
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
 

3. **Install Dependencies**
    pip install -r requirements.txt


4. **Set Up Database**
    - Configure the database in `config.py`.
    - Run database migrations to set up required tables.

  
    flask db init
    flask db migrate
    flask db upgrade


---

## Configuration

1. Create a `.env` file for sensitive configurations such as `SECRET_KEY`, `DATABASE_URI`, etc.
2. Modify `config.py` if additional custom configuration is required.

---

## Usage

1. **Run the Application**
    flask run


2. **Access the Application**
   - Visit `http://127.0.0.1:5000` in your browser.

3. **Navigate the Features**
   - **Home**: Upload images and view license plate recognition results.
   - **Dashboard**: See metrics and apply monthly filters for detailed insights.

---

## Project Structure

```plaintext
license-plate-recognition-system/
├── app/
│   ├── static/                 # CSS and JavaScript files
│   ├── templates/              # HTML templates
│   ├── models.py               # Database models
│   ├── routes.py               # Application routes
│   └── __init__.py             # Flask app setup
├── migrations/                 # Database migrations
├── config.py                   # Configuration settings
├── requirements.txt            # Dependencies
└── README.md                   # Project documentation
```

---

## Technologies Used

- **Frontend**: HTML, CSS.
- **Backend**: Python, Flask, SQLAlchemy for ORM.
- **Database**: SQLite 

---

## Contributing

Contributions are welcome! If you have suggestions or would like to contribute to the project, please:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License

