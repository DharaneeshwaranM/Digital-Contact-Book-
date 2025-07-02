📖 Digital Contact Book

A desktop application built with Python and Tkinter that allows users to add, view, search, update, and delete contact information. The application uses SQLite as its backend database for storing contact data persistently.


---

🚀 Features

✅ Add new contact with name, phone, email, and address

📋 View all saved contacts in a list

🔍 Search contacts by name

📝 Update contact details

❌ Delete existing contact

🗃️ Uses SQLite for local database storage

🧑‍💻 Simple and user-friendly GUI using Tkinter



---

🛠 Technologies Used

Python 3.x

Tkinter - for GUI

SQLite - for backend storage

OOP & File Handling



---

💻 How It Works

1. The application initializes the SQLite database (contacts.db) if it doesn't exist.


2. The user can enter contact details using the GUI.


3. All contacts are displayed in a listbox.


4. Contacts can be selected for update or deletion.


5. Searching is done by name using a search entry box.




---

▶️ How to Run

1. Install Python 3.x (if not already installed)


2. Save the script as contact_book.py


3. Open terminal or command prompt


4. Run the script:



python contact_book.py

5. The GUI will launch and the database will be created automatically.




---

🏗 System Design (Conceptual)

+-------------------+
|   Tkinter GUI     |
+-------------------+
         |
         v
+-------------------+
|   CRUD Operations |
+-------------------+
         |
         v
+-------------------+
|   SQLite Database |
+-------------------+


---

🔮 Future Enhancements

📤 Export contacts to CSV/Excel

🏷️ Add tags or categories to contacts

☁️ Cloud backup or sync option

🖼️ Allow adding profile images to contacts



---

📁 File Structure

├── contact_book.py           # Main Python script
├── contacts.db               # SQLite database (auto-generated)
├── README.md                 # Project documentation
