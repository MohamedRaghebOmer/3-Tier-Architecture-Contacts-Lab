# Learn-Three-Tier-Architecture 🚀

A practical implementation of the Three-Tier Architecture pattern using C# and .NET. This project serves as a learning resource for structuring scalable and maintainable applications by separating concerns into distinct layers.

## 🏗️ Project Structure

The solution is divided into three main layers:

* **Contacts.ConsoleApp (Presentation Layer):** The user interface (CLI) that handles user input and displays information.
* **Contacts.Business (Business Logic Layer):** Contains the core logic and validation rules. It acts as a bridge between the UI and the data.
* **Contacts.Data (Data Access Layer):** Responsible for direct communication with the database (CRUD operations).

## 🛠️ Tech Stack

* **Language:** C#
* **Framework:** .NET
* **Database:** SQL Server (Database backup included as ContactsDB.bak).

## 🚀 Getting Started

1. **Clone the repo:**

```bash
git clone https://github.com/MohamedRaghebOmer/Learn-Three-Tier-Architecture.git
```

2. **Database Setup:**

* Restore the `ContactsDB.bak` file in your SQL Server instance.

3. **Configuration:**

* Update the connection string in the `Contacts.Data` layer to match your local server settings.

4. **Run:**

* Set `Contacts.ConsoleApp` as the startup project and run the application.
