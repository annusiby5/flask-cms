# FlaskCMS


## Description
This project is a Contact Management System built using Flask. It provides a structured way to manage contacts, allowing users to add, view, delete and search their contact information and account along with pagination through a web interface.



## Features
- User registration and login
- Add, edit, search, view and delete contacts
- Notifications while performing an action
- Edit or delete user account
- Responsive design with a user friendly interface

## Installation
To set up this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/annusiby5/flask-cms.git
   cd flask-cms
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database:
   - Ensure you have SQLite installed.
   - The database will be created automatically when you run the application.

## Usage
To run the application, execute the following command:
```bash
python app.py
```
Visit `http://127.0.0.1:5000` in your web browser to access the application.

## Technologies Used

* Python
* Flask
* SQLite3
* HTML
* CSS
* JavaScript
* Jinja2

## Project Structure

```text
flask-cms/
│
├── app.py
├── model.py
├── templates/
├── static/
│   └── css/
│   └── images/
│   └── js/
├── instance/
│   └── contacts.db
├── LICENSE
├── README.md
└── requirements.txt
```

## License

This project is open source and available under the MIT License.