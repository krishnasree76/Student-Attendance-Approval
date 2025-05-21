**STUDENT ATTENDANCE APPROVAL - Effortless approval of student attendance**

This was our **first full Python project** completed during the **WISE session**. The idea of our project came from the issue we face while seeking **attendance permission during crucial periods**. To overcome this problem, we came up with this idea. The core interface is provided by the **main.py** file, offering a **GUI to interact with the system**. We used **Python 3.12.0** for coding. It's important to note that the system relies on **maintaining text files in the same location as the Python files** for proper functionality. Widgets such as **buttons, entry boxes, etc.** are used in this project.

The goal of the **Student Attendance Approval System** is to provide **convenience for both teachers and students**. Users can access this **anytime, anywhere with an internet connection**. Let's go into the project in detail to understand its working from both **student** and **admin** perspectives.

**Before getting into the project**, we need to make sure that we have a **database for student and admin details** to ensure the efficient working of the system.

**The starting page** of our project contains the **login details of student and admin**. After successfully entering the credentials, it will lead us to the corresponding **connect page**.

**STUDENT DASHBOARD:**  
After entering the student details, we are directed to the **student dashboard**, which contains the **student profile** and two options:  
1) **Make Request**  
2) **View Request**  

In the **Make Request** page, it will ask for some details like:  
**ID, Name, Branch, From Date, To Date, Periods**, and **Reason for seeking permission**.  
After clicking the **Enter** button, the request will be submitted to the **admin**.

In the **View Request** page, the student can **check the status** of their request.

**ADMIN DASHBOARD:**  
After entering the admin details, we are directed to the **admin dashboard**, which contains the **admin profile** and two options:  
1) **Student Requests**  
2) **Student Details**  

In **Student Requests**, it shows the **requests posted by the students**, and the admin can either **accept or decline** the request based on the submitted reason.

After accepting or declining, the **status is updated** and shown to the student.

**Conclusion:**  
The project is **useful and convenient for both students and teachers**. By using **Python and SQL technologies**, it provides a **user-friendly platform**, facilitating communication between **staff and students** effectively. With its **interfaces and comprehensive features**, the system offers **efficiency** and ease of use.

---

**Installation**

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/krishnasree76/Student-Attendance-Approval.git
   cd Student-Attendance-Approval
