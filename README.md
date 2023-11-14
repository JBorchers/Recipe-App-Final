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

Once the development server is running, you can access the Recipe App and explore its features.

1. **Homepage:**
   - Navigate to [http://localhost:8000](http://localhost:8000) in your web browser.
   - The homepage provides an overview of the app, showcasing its user-friendly design and features.

2. **Login:**
   - Click on the "Login" button on the homepage to access the authentication page.
   - Enter your user credentials to proceed.

   ![Login](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/login.png)

3. **Recipe List View:**
   - Authenticated users will be directed to the list view, displaying all recipes.
   - Explore the list view to see a comprehensive overview of available recipes.

   ![List View](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/list_view.png)

4. **Recipe Details:**
   - Click on a recipe to view detailed information.
   - Multiple screenshots showcase different aspects of the recipe details.

   ![Details View 1](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/detail_view1.png)
   
   ![Details View 2](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/detail_view2.png)

6. **Add Recipe:**
   - Authenticated users can contribute to the app by adding a new recipe.
   - The "Add Recipe" page allows users to input recipe details.

   ![Add Recipe](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/add_recipe.png)

7. **Filtering:**
   - Utilize the filtering options to narrow down recipes based on various criteria.
   - Screenshots demonstrate the filter functionality.

   ![Filter](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter.png)

8. **Filter Charts:**
   - Visualize recipe data with interactive charts.
   - Screenshots showcase bar, pie, and line charts based on applied filters.

   ![Filter Bar Chart](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter_bar_chart.png)
   ![Filter Pie Chart](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter_pie_chart.png)
   ![Filter Line Chart](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/filter_line_chart.png)

9. **Logout:**
   - When done, click on the "Logout" button to securely log out of the app.

   ![Logout](https://github.com/JBorchers/cfPython_Achievement2/raw/main/Exercise_2.8/screenshots/logout.png)
