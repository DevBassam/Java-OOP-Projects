<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Library Management System</title>
</head>
<body>
    <h1>Library Management System</h1>
    <p>Welcome to the Library Management System project. This project is designed to manage books and members in a library. It supports adding, updating, and removing books and members, as well as borrowing and returning books.</p>
    
    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#overview">Project Overview</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#techniques">Techniques Used</a></li>
        <li><a href="#project-flow">Project Flow</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#license">License</a></li>
    </ul>
    
    <h2 id="overview">Project Overview</h2>
    <p>The Library Management System is a Java-based application that provides a set of functionalities for managing a library's book collection and its members. The application allows users to add, update, and remove books and members, as well as track book loans and returns.</p>
    
    <h2 id="features">Features</h2>
    <ul>
        <li>Add, update, and remove books from the catalog.</li>
        <li>Add, update, and remove members.</li>
        <li>Borrow and return books with constraints on the number of books a member can borrow.</li>
        <li>Increase the number of copies of a book if it already exists in the catalog.</li>
        <li>Display available books with the number of copies in stock.</li>
        <li>Ensure members cannot borrow more than two different books at a time.</li>
        <li>Validate data inputs such as ISBN, dates, member IDs, and phone numbers.</li>
    </ul>
    
    <h2 id="techniques">Techniques Used</h2>
    <p>This project uses the following techniques:</p>
    <ul>
        <li><strong>Object-Oriented Programming (OOP)</strong>: Classes like <code>Book</code>, <code>Member</code>, and <code>Library</code> are used to model the real-world entities and their interactions.</li>
        <li><strong>Exception Handling</strong>: Custom error messages and validation checks are implemented to handle invalid inputs and exceptional cases.</li>
        <li><strong>Data Validation</strong>: Validations for ISBN, dates, member IDs, and phone numbers ensure correct data entry.</li>
        <li><strong>Collections Framework</strong>: <code>HashMap</code> and <code>HashSet</code> are used for storing and managing books and members efficiently.</li>
        <li><strong>Command-Line Interface (CLI)</strong>: The application interacts with users via a CLI, allowing them to perform various operations.</li>
    </ul>
    
    <h2 id="project-flow">Project Flow</h2>
    <p>The flow of the project is as follows:</p>
    <ol>
        <li><strong>Initialization</strong>: The application initializes the library with an empty catalog and member directory.</li>
        <li><strong>User Interaction</strong>: Users interact with the CLI to choose operations such as adding a book, removing a member, or borrowing a book.</li>
        <li><strong>Data Handling</strong>: Based on the user’s choice, the application performs the required operation, such as updating the book catalog or member records.</li>
        <li><strong>Validation</strong>: User inputs are validated to ensure correctness before processing.</li>
        <li><strong>Feedback</strong>: The system provides feedback to the user, such as success or error messages, based on the outcome of the operation.</li>
    </ol>
    
    <h2 id="usage">Usage</h2>
    <p>To use this application:</p>
    <ol>
        <li>Run the <code>Main</code> class.</li>
        <li>Follow the prompts to perform actions such as adding books or members, borrowing or returning books, etc.</li>
        <li>Refer to the CLI options to choose different functionalities and perform operations as needed.</li>
    </ol>
    
    <h2 id="contributing">Contributing</h2>
    <p>Contributions are welcome! If you would like to contribute to the project, please fork the repository and submit a pull request with your changes. Make sure to follow the coding standards and include relevant documentation.</p>
    
    <h2 id="license">License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>
</body>
</html>