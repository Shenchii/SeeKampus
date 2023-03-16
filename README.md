# SeeKampus
Seekampus is a Flask-based a school recommender system which utilized predicted board examination passing rates of the colleges in CALABARZON and NCR. It was designed to provide college recommendations based on the users’ preferences in terms of the course, location, and tuition fee. This project is developed by Hinggan, Mutya P.,
Lacsam, Shane Adrian A.,
Mortel, John Raiden C.,
Siena, Bernadette B. as a part of City College of Calamba coursework.

## Installation
To run the Seekampus web application on your local machine, follow these steps:

Clone the repository using the following command:

`git clone https://github.com/username/seekampus.git`


Replace username with your GitHub username.
Navigate to the project directory:

`cd seekampus`


Create a virtual environment and activate it:

`python3 -m venv venv`
`source venv/bin/activate`


Install the required dependencies:

`pip install -r requirements.txt`


Set the environment variables:

Create a .env file in the project directory
Define the following variables:

`FLASK_APP=seekampus
FLASK_ENV=development`


Initialize the database:

`flask init-db`

Run the Flask app:

`flask run`


The Seekampus app should now be running on your local machine at http://localhost:5000/.

Usage
After installation, you can access the Seekampus web application by opening a web browser and navigating to http://localhost:5000/.
