# 📞 Java Contact Book Manager (OOP Lab Project)

This is a **Contact Book Management System** developed in **Java** using the **Apache NetBeans IDE**. It was created as an OOP (Object-Oriented Programming) laboratory project to demonstrate fundamental principles, with a focus on implementing custom **data persistence using File I/O**.

---

## ✨ Features

The application provides a standard set of contact management features:

* **Create (Add) Contact:** Input and save new contact records (Name, Phone, Email, etc.).
* **Read (View) Contacts:** Display all stored contacts from the data file.
* **Update (Edit) Contact:** Modify the details of an existing contact.
* **Delete Contact:** Remove a contact record from the system.
* **Search:** Find contacts based on criteria (e.g., searching by name).

---

## 🛠️ Technologies & Key Concepts

| Category | Component | Description |
| :--- | :--- | :--- |
| **Language** | Java Development Kit (JDK) | Core programming language. |
| **IDE** | Apache NetBeans | Development environment for coding and testing. |
| **Persistence** | **Plain Text File (`contacts.txt`)** | Simple storage solution using Java File I/O. |
| **OOP** | Encapsulation | Private class fields accessed via Getters/Setters. |
| **OOP** | Inheritance & Polymorphism | Base `Contact` class extended by potential subclasses (if implemented). |
| **I/O** | `java.io` Package | Use of classes like `FileReader`, `FileWriter`, `BufferedReader`, and `PrintWriter` for data handling. |

---

## 💾 Data Persistence Model

A key feature of this project is the manual implementation of data saving and loading:

1.  **Storage File:** All contact data is stored in a plain text file named **`contacts.txt`** (located in the project root/working directory).
2.  **Saving Data:** When a contact is added, edited, or deleted, the `ContactManager` class writes the entire list of contacts back to the `contacts.txt` file.
3.  **Loading Data:** Upon application startup, the system reads line-by-line from `contacts.txt`, parses the data using a delimiter (e.g., commas or pipes), and reconstructs the `Contact` objects.

> **Example line format in `contacts.txt` (Hypothetical):**
> `John Doe|555-1234|john@example.com`

---

## ⚙️ How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository URL Here]
    ```
2.  **Open in NetBeans:**
    * Launch **Apache NetBeans IDE**.
    * Go to `File` > `Open Project...` and navigate to the cloned folder.
3.  **Compile and Run:**
    * Right-click on the main project folder in the Projects window.
    * Select **Run**.
    * *(Alternatively, press `F6`)*

---

## 👨‍💻 Author

* **[Your Name]** - *Initial Work* - [Your Student ID] / [Link to your GitHub Profile (optional)]