# ASSIGNMENT_ENVERUS

### To run the project on your local system :

1. Clone the repository to your system using this command,
   ```sh
   git clone https://github.com/mayank2478/ASSIGNMENT_ENVERUS.git
   ```

2. cd into the repository using,
   ```sh
   cd <project directory>
   ```

3. Run the following command to install all the necessary dependencies and migrate.
   ```sh
   pip install -r requirements.txt
   ```
   ```sh
   python manage.py migrate
   ```

4. Run the following command to create a superuser i.e., admin.
   ```sh
   python manage.py createsuperuser
   ```

5. Use this command to run the project on your localserver and keep the terminal running.
   ```sh
   python manage.py runserver
   ```

If all previous steps have been done correctly, the server will be live on port 8000.
Link : http://localhost:8000/  or  http://127.0.0.1:8000