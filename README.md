# 📞 Java Contact Book Application

This is a **Contact Book Management System** developed in Java using the **NetBeans IDE**. It was created as an OOP (Object-Oriented Programming) laboratory project to demonstrate key concepts like **Encapsulation**, **Inheritance**, and **Polymorphism**.

---

## ✨ Features

The application allows the user to manage a list of contacts with the following functionalities:

* **Add New Contact:** Allows input of contact details (e.g., Name, Phone, Email).
* **View All Contacts:** Displays a list of all stored contacts.
* **Search Contact:** Find a contact based on a specific criteria (e.g., Name or Phone Number).
* **Edit Contact:** Modify the details of an existing contact.
* **Delete Contact:** Remove a contact from the list.
* **Persistence:** Contacts are saved and loaded (e.g., using file I/O or a simple database like SQLite, if implemented).

---

## 🛠️ Technologies Used

* **Programming Language:** Java Development Kit (JDK)
* **Integrated Development Environment (IDE):** Apache NetBeans
* **User Interface:** Java Swing/AWT (or Console-based, depending on your implementation)
* **OOP Concepts:** Inheritance, Encapsulation, Polymorphism, Abstraction.

---

## ⚙️ How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository URL Here]
    ```
2.  **Open in NetBeans:**
    * Launch **NetBeans IDE**.
    * Go to `File` > `Open Project...` and navigate to the cloned folder.
3.  **Run the Application:**
    * Right-click on the project folder in the Projects window.
    * Select **Run**.
    * *(Alternatively, press `F6`)*

---

## 📚 OOP Implementation Details

This project utilizes OOP principles through the following structure:

* **`Contact` Class:** The base class (potentially abstract) containing common contact fields (Name, Phone Number) and methods.
* **Subclasses (Inheritance):** Depending on your design, you might have subclasses like:
    * `PersonalContact` (e.g., adds a Birthday field)
    * `BusinessContact` (e.g., adds a Company Name field)
* **`ContactManager` Class:** Handles the main business logic, such as adding, searching, and deleting contacts, typically using a `java.util.ArrayList` or similar data structure to hold `Contact` objects.
* **Encapsulation:** All class fields are declared as `private` and accessed via public `getter` and `setter` methods.

---

## 👨‍💻 Author

* **[Your Name]** - *Initial Work* - [Your Student ID] / [Link to your GitHub Profile (optional)]

---
