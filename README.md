# Student Enrollment Form Project

## Overview
This project is a **Student Enrollment Form** created using **HTML**, **CSS**, and **JavaScript**. The form allows users to register, update, and reset student data. The data is stored in **JsonPowerDB** (JPDB), a real-time database known for its easy integration and minimal setup. The form functionality has been tested using **Talend API Tester** to ensure that the data operations work correctly.

## Features
- **Student Registration**: Allows input of student details, such as roll number, name, class, birth date, address, and enrollment date.
- **Update Functionality**: Enables modification of existing student data.
- **Reset Functionality**: Clears the form for new data entry.
- **Data Storage**: Integrated with **JsonPowerDB** for seamless database operations.
- **API Testing**: Utilizes **Talend API Tester** for testing and verifying API requests and responses.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Database**: JsonPowerDB
- **API Testing Tool**: Talend API Tester
- **Libraries**:
  - [Bootstrap](https://getbootstrap.com) for responsive design
  - jQuery for simpler DOM manipulation

## How to Run the Project
1. Clone the repository:

   git clone https://github.com/yourusername/student-enrollment-form.git
   cd student-enrollment-form
   

2. Open the `index.html` file in a web browser.

3. Ensure that the **JsonPowerDB** server is running and configured properly.

## JsonPowerDB Integration
JsonPowerDB is used for:
- **Storing student data**: Each student record is saved using a unique roll number.
- **Retrieving student data**: Data is fetched based on the roll number to check for existing records.
- **Updating student data**: Existing records can be modified and updated in the database.

## Testing with Talend API Tester
- **Step 1**: Open **Talend API Tester**.
- **Step 2**: Configure a `POST` request with the endpoint URL pointing to your JsonPowerDB server (e.g., `http://<your-jsonpowerdb-server-url>/api/iml`).
- **Step 3**: Add the request body and headers as needed and send the request.
- **Step 4**: Verify the response to ensure data is being stored or retrieved correctly.

## Project Structure
```
student-enrollment-form/
│
├── index.html        # Main HTML file containing the form structure
├── style.css         # CSS file for custom styling
├── index.js          # JavaScript file for form functionality
└── README.md         # Project documentation
```


---

**Note**: This is a sample README file. Make sure to update sections like repository link, contact information, and file paths as per your project details.
```

Feel free to add any specific details, such as screenshots or further instructions, to tailor the README to your needs.
