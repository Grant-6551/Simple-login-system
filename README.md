## Simple PHP Login System
A simple, secure PHP login system with essential features including user authentication, a personalized dashboard, profile viewing, and profile updating.

# Features
User Authentication: Secure login and logout.
Dashboard: Personalized user dashboard after login.
Profile Page: View user profile information.
Update Profile: Users can update their profile details.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/repo-name.git
Navigate to the project directory:

bash
Copy code
cd repo-name
Set up your database:

Import the provided database.sql file into your MySQL database.
Update config.php with your database credentials.
Start the local server:

bash
Copy code
php -S localhost:8000
Access the application:

Open your browser and go to http://localhost:8000.
# Usage
Register a new account or use the provided credentials.
After logging in, you’ll be redirected to your dashboard.
Access the profile page to view your details.
Use the update profile page to modify your information.

# File Structure
index.php - Main landing page with login functionality.
dashboard.php - User dashboard after successful login.
profile.php - Displays user profile information.
update-profile.php - Form to update user details.
config.php - Database configuration file.
functions.php - Contains helper functions for the application.

# Security Features
Password hashing for secure authentication.
Input validation to prevent SQL injection.
Session management to protect user data.

License
This project is open-source and available under the MIT License.
