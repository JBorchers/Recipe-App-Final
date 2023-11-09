# Recipe-App-Final


![Homepage](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/home_page.png)

This recipe app allows users to create, discover and sort through a wide range of recipes. With its intuitive user interface and robust features, the app streamlines the task of managing and exploring recipes.

## Getting Started

Follow these steps to get started with the Recipe App:

### Prerequisites

Before you begin, make sure you have the following installed on your machine:

- [Python 3.6+](https://www.python.org/downloads/)
- [Django 3](https://docs.djangoproject.com/en/3.2/intro/install/)

### Clone the Repository

Clone the project repository from GitHub to your local machine using the following command:
```
bash
git clone https://github.com/JBorchers/Recipe-App-Final.git
```

## Install Dependencies

Navigate to the project directory and install the required Python modules by running:
`pip install -r requirements.txt`

## Database Configuration

In the project's settings file (settings.py), configure the database settings:
- For development, use SQLite. A default configuration is provided.
- For production, set up PostgreSQL and update the configuration accordingly.

## Run Migrations

Apply the database migrations using the following commands:
```
python manage.py makemigrations
python manage.py migrate
```

## Start the Development Server

Run the below command to start a local development server:
`python manage.py runserver`

## Access the App

Open a web browser and navigate to http://localhost:8000 to access the application.




After clicking the button on the homepage, the user is directed to a login page. They will enter their user credentials and then be directed to the next page.
![Login](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/login.png)

list view
![List View](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/list_view.png)

details
![Details View 1](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/detail_view1.png)
![Details View 2](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/detail_view2.png)

add recipe
![Add Recipe](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/add_recipe.png)

filter
![Filter](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter.png)

filter bar chart
![Filter Bar Chart](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter_bar_chart.png)

filter pie chart
![Filter Pie Chart](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter_pie_chart.png)

filter line chart
![Filter Line Chart](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter_line_chart.png)

logout
![Logout](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/logout.png)
