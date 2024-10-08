```markdown
# Weather Application

This is a simple weather application built using Django. It allows users to enter a city name and get the current weather information for that city. The application also keeps a history of searched cities along with their temperatures.

## Features

- Get current weather information for a city.
- Display weather condition, temperature, and wind information.
- Store and display search history with city names, temperatures, and search dates.

## Prerequisites

- Python 3.12.4
- Django 5.1

## Setup Instructions

1. **Clone the repository**:

    ```sh
    git clone https://github.com/ankitshaw09/weather-application.git
    cd weather-application
    ```

2. **Create a virtual environment**:

    ```sh
    python -m venv env
    ```

3. **Activate the virtual environment**:

    - On Windows:

        ```sh
        env\Scripts\activate
        ```

    - On macOS/Linux:

        ```sh
        source env/bin/activate
        ```

4. **Install the required packages**:

    ```sh
    pip install django requests
    ```

5. **Create and apply migrations**:

    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Run the development server**:

    ```sh
    python manage.py runserver
    ```

7. **Open the application**:

    Open your web browser and go to `http://127.0.0.1:8000/` to see the weather application in action.

## Project Structure

- `weather_project/`: The main project directory.
- `weather/`: The application directory containing models, views, and templates.
- `weather/migrations/`: Directory containing database migration files.
- `weather/templates/weather/`: Directory containing HTML templates.
- `db.sqlite3`: SQLite database file.
- `manage.py`: Django management script.

```
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
