


This repository contains the source code for a real-time chat web application developed using PHP with MySQL & JavaScript. The application allows users to sign up, log in, and engage in real-time text-based communication with other users.

# Features
- User signup with name, email, password, and image.
- User login authentication.
- Real-time messaging between users.
- User status indication (online/offline).
- Automatic scrolling in chat boxes.
- User logout functionality.


# Setup Instructions

1. **Clone the Repository:** Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/Narsimha1202/Echo-Chat-Real-time-Web-Communications.git
   ```

   ```
   cd ChatApp
   ```
2. **Move Files:** Move the `ChatApp` folder to the `htdocs` directory of your XAMPP installation.

3. **Database Setup:** 
   - Start Apache and MySQL from the XAMPP control panel.
   - Open your web browser and go to `localhost/phpmyadmin`.
   - Create a new database named `chatapp`.
   - In the `ChatApp` folder, locate the SQL file (`database.sql`) and import it into the `chatapp` database.

4. **Configuration:** Navigate to the `ChatApp` folder and locate the `.env` file. Update the database connection settings if necessary.

5. **Accessing the Application:** Open your web browser and navigate to `localhost/ChatApp` to access the chat application.

# Usage
- Upon accessing the application, sign up with your details or log in with existing credentials.
- Once logged in, you'll be directed to the user's page where you can see other users who have signed up.
- Click on a user to start a chat session.
- Messages sent between users will appear in real-time in their respective chat boxes.
- Logout from the application anytime using the provided logout button.



# Preview
# Signup: ![Signup](https://github.com/Narsimha1202/ChatApp-using-PHP-MySQL-JavaScript/assets/98202100/f9ad2ba6-aee0-4399-bad1-bd59e080057d)
# Login: ![Login](https://github.com/Narsimha1202/ChatApp-using-PHP-MySQL-JavaScript/assets/98202100/7716ebbe-ae71-4e0e-b2a1-4f8e9e7b0d19)
# Interface: ![Interface](https://github.com/Narsimha1202/ChatApp-using-PHP-MySQL-JavaScript/assets/98202100/d77eb711-1eff-4564-a25d-34209091ebe8)
# Chat: ![Chat 2](https://github.com/Narsimha1202/ChatApp-using-PHP-MySQL-JavaScript/assets/98202100/75f5d470-69bd-45a8-a2c9-1ac46801cc43)

# SQL Database: ![SQL Database](https://github.com/Narsimha1202/ChatApp-using-PHP-MySQL-JavaScript/assets/98202100/f0da6b3f-0f1f-4b7e-9e21-cc4cf95f5df0)
# Users Shown in DB: ![Users shown in DB](https://github.com/Narsimha1202/ChatApp-using-PHP-MySQL-JavaScript/assets/98202100/fc17132b-09c5-4762-a66a-363608e8e57d)
# Messages stored in DB: ![Messages stored in DB](https://github.com/Narsimha1202/ChatApp-using-PHP-MySQL-JavaScript/assets/98202100/bb2af355-a086-4d13-857f-ffdc0f9a367f)

# Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow the standard GitHub workflow:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.

For any further inquiries or issues, feel free to contact at [gundarapunarsimhareddy@gmail.com](mailto:gundarapunarsimhareddy@gmail.com).

Happy Chatting! 🚀
