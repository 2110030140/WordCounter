## Word and Character Counter GUI with MySQL Integration in Java

This project provides a simple graphical user interface (GUI) application implemented in Java for counting words and characters in a text input. It consists of two separate implementations: one using Swing and another utilizing AWT for the GUI components. Additionally, it incorporates a MySQL database for storing and retrieving text input data.

## Features:
•	Counts total words and characters in the provided text.
•	Allows changing background and text color of the text area.
•	Integrates with a MySQL database for storing text input data.
•	Offers a simple, intuitive user interface.

## Technologies Used:
•	Java
•	Swing (for the Word Character Counter implementation)
•	AWT (for the Character Word Count Tool implementation)
•	MySQL (for database integration)

## How to Use:
1. Clone the repository to your local machine.
2. Set up a MySQL database with the required schema (details provided in the database setup instructions).
3. Open the project in your favorite Java IDE.
4. Compile and run the desired Java file (`WCC.java` for Word Character Counter, `CharCount.java` for Character Word Count Tool).
5. Input text into the provided text area.
6. Click the "Word" button to count words or the "Character" button to count characters in the text.
7. Optionally, use the "Pad Color" and "Text Color" buttons to customize the appearance of the text area.

## Database Setup Instructions:
1. Create a MySQL database named `word_character_counter`.
2. Execute the SQL script provided in the `database_setup.sql` file to create the required table (`text_data`).
3. Update the database connection details (`username`, `password`, `host`, `port`) in the Java files where necessary.

## Files:
1. `WCC.java`: Contains the implementation of Word Character Counter using Swing.
2. `CharCount.java`: Implements the Character Word Count Tool using AWT.
3. `README.md`: Instructions and information about the project.
4. `LICENSE`: License information.
5. `database_setup.sql`: SQL script for setting up the MySQL database.

## Contributors:
-THANDRA LEEKHITHA REDDY 

## Feedback and Contributions:
Feedback and contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## About:
This project was created as a learning exercise in Java GUI programming with MySQL integration. It aims to provide a simple yet functional tool for counting words and characters in text input while utilizing a database for data storage.

Contact:
For any inquiries or further information, you can contact leekhitha.reddy@gmail.com

Thank you for using our Word and Character Counter GUI with MySQL Integration in Java! We hope you find it useful.



