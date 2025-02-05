### Management System for Canine Grooming "CANINA ESTÉTICA" 🐩
### Project Description:
The system is an application designed for the canine grooming salon "CANINA ESTÉTICA". Its main goal is to store and manage data of client pets and their owners through an intuitive and user-friendly form. The application allows registering detailed information, such as:
![image](https://github.com/user-attachments/assets/5777a219-3df5-4aa3-aeea-a7932f8fd089)

## Pet Data:

- Client Number
- Dog Name
- Breed
- Color
- Allergies
- Special Care
- Observations

## Owner Data:

- Owner ID
- Owner Name
- Phone Number

The application features a graphical user interface (GUI) that facilitates interaction and data management. All information is stored in a database, allowing employees to access and manage records in the future.

## User Interface Design
### 1. Data Entry Interface
**Title:** "Data Entry"
![image](https://github.com/user-attachments/assets/7fe3e59d-72c3-4d2d-824d-12ffef678e87)

**Input Fields:**
![image](https://github.com/user-attachments/assets/f0d38d48-d2a8-4fc0-840e-40ba292aee4c)

- Dog Name (Example: 'David')
- Breed (Example: 'Border Collie')
- Color (Example: 'Black and White')
- Allergic (Example: 'No')
- Special Care (Example: 'Yes')
- Owner Name (Example: 'Keury')
- Owner Phone (Example: '8099903199')
- Observations (Optional Field)

**Buttons:**

- **Clear:** Clears all input fields.
- **Cancel:** Cancels the current operation.
- **Save:** Saves the entered information.
- **Confirmation Message:** "Saved Successfully" (indicates that the data has been saved successfully).

### 2. Data Display Interface
**Title:** "Data Display"
![image](https://github.com/user-attachments/assets/6f01f75c-c87a-4fd2-8bc5-f8cde6f29852)

**Data Table:**

- **Headers:**
  - Num: Record number.
  - Name: Dog's name.
  - Color: Dog's color.
  - Breed: Dog's breed.
  - Allergic: Indicates if the dog is allergic.
  - Sp. Care: Special care, if the dog needs special attention.
  - Owner: Owner's name.
  - Phone: Owner's phone number.

- **Data Rows:** Each row represents a dog's record with the corresponding information. For example:
  - Name: David
  - Color: Black and White
  - Breed: Border Collie
  - Allergic: No
  - Sp. Care: Yes
  - Owner: Keury
  - Phone: 8099903199

**Toolbar:**

- Icons for functionalities like modifying or deleting records.

### 3. Data Modification Interface
**Title:** "Data Modification"
![image](https://github.com/user-attachments/assets/4ba9b552-36f2-47b6-8148-1af7fb97d14b)

**Buttons:**

- **Clear:** Clears all input fields.
- **Search:** Allows searching for a specific record to modify.
- **Save Changes:** Saves the modifications made to the data.
- **Confirmation Message:** "Edit Completed Successfully".
![image](https://github.com/user-attachments/assets/5c150196-e8fd-4df2-bcb3-1544b4cd58ea)

### 4. Record Deletion
When selecting the option to delete a record, a confirmation message is displayed: "Pet Deleted Successfully".
![image](https://github.com/user-attachments/assets/b3f805ab-5a5b-4767-bdad-39e43e8c674c)

## Key Features
- **Data Entry:** Allows entering new records of pets and owners.
- **View Data:** Displays stored records in a table.
- **Modify Data:** Allows editing the information of an existing record.
- **Delete Records:** Deletes a record from the database.
- **Exit:** Closes the application.

## Technologies Used

- **Programming Language:** [Java]<a href="https://www.java.com/en/">
    <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  </a>

- **Database:** [WampServer]<a href="https://www.wampserver.com/en/" target="_blank">
    <img src="https://img.shields.io/badge/WampServer-FF8800.svg?style=for-the-badge&logo=windows&logoColor=white" 
      alt="WampServer"/> 
</a>

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/canina-estetica.git
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

### Contributions 👌

Contributions are welcome! If you want to improve this project, follow these steps:

1. Fork the repository.
2. Create a branch for your new feature (`git checkout -b new-feature`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin new-feature`).
5. Open a Pull Request.
