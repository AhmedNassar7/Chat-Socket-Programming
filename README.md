# Chat Application

This project is a **real-time chat application** that enables users to exchange messages over the network using **TCP/IP connectivity** through socket programming. It supports real-time communication and stores chat data securely in a **SQL database**. The application features a user-friendly graphical interface designed with **Java Swing**, and the code is modular and maintainable, adhering to **Object-Oriented Programming (OOP)** principles.

## Features

- **Real-time Messaging**: Users can send and receive messages instantly.
- **Modular Codebase**: The application is developed using OOP principles, making it modular, easy to maintain, and extendable.
- **Database Management**: Chat logs are securely stored and retrieved from a **SQL database**.
- **User-friendly GUI**: Designed with **Java Swing** for an intuitive and responsive user interface.
- **Data Support**: Supports the exchange of text, files, and other types of data.

## Technologies Used

- **Java**: Core application logic, including OOP principles for maintainability.
- **Java Swing**: For the design and development of the graphical user interface (GUI).
- **Socket Programming**: For TCP/IP connectivity and real-time communication.
- **SQL**: To manage the storage and retrieval of chat messages.
- **NetBeans**: Integrated Development Environment (IDE) used for development and testing.

## Project Structure

The project is divided into the following main components:

- **Client**: Handles user-side operations, including sending and receiving messages and displaying the GUI.
- **Server**: Manages multiple client connections, message broadcasting, and communication handling.
- **Data**: Contains the SQL database files, which store chat history and other necessary data.
- **Database Schema (pronewa.sql)**: The SQL schema used to set up the database for message storage.

## How to Run the Application

1. **Requirements**:
   - Java JDK (8 or later)
   - NetBeans IDE
   - MySQL or any SQL-compatible database

2. **Steps**:
   - Clone the repository to your local machine.
   - Open the project in **NetBeans**.
   - Set up the SQL database using the provided `pronewa.sql` file.
   - Configure the database connection details in the server code.
   - Run the server from the `Server` package.
   - Launch the client from the `Client` package.
   - Multiple clients can connect to the server to start exchanging messages in real time.

## Database Setup

To set up the database:

1. Create a new database using the SQL server of your choice.
2. Run the SQL script `pronewa.sql` to create the necessary tables for storing chat messages.
3. Update the connection details in the server code to match your database credentials.

## File Structure

- **Client/**: Contains the code for the client-side application.
- **Server/**: Contains the code for the server-side application.
- **Data/**: Includes the SQL schema file `pronewa.sql`.
- **README.md**: Documentation for the project.

## Contributions

Feel free to open a pull request or report issues if you would like to contribute to the project. Suggestions and improvements are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

