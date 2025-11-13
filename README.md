# 📚 **EduFee Manager**

A simple and efficient **Student Fee & Management System** built using **Java, JSP, JDBC, and MySQL**.
It allows admins and accountants to seamlessly manage student records, fee details, and account operations from a browser-based interface.

---

## 🚀 **Features**

### 👤 **Admin Module**

* Add new accountants
* View all accountants
* Delete accountants
* Secure login/logout

### 💼 **Accountant Module**

* Add new students
* View student details
* Edit / Update student information
* Delete students
* Check due fees
* Secure login/logout

---

## 🛠️ **Tech Stack**

* **Java** (Core + JDBC)
* **JSP / Servlets**
* **MySQL Database**
* **Tomcat Server**
* **HTML / CSS** (Basic UI)

---

## 📁 **Project Structure**

```
├── Admin.java
├── AdminDao.java
├── Login.jsp
├── LoginModel.java
├── Student.java
├── Student.jsp
├── administration.jsp
├── README.md
```

---

## 🗄️ **Database Setup (MySQL)**

1. Create a database:

```sql
CREATE DATABASE edufee;
```

2. Create required tables
   (Admin, Accountant, Student, Fee table—based on your Java code structure)

3. Update database credentials in your DAO/connection file:

```java
String url = "jdbc:mysql://localhost:3306/edufee";
String username = "root";
String password = "your-password";
```

---

## ▶️ **How to Run the Project**

1. Clone the repository:

```bash
git clone https://github.com/MallikaSingh773/EduFee-Manager.git
```

2. Import into any Java IDE (IntelliJ / Eclipse / NetBeans)

3. Add MySQL Connector JAR to the project `lib`

4. Deploy on **Apache Tomcat**

5. Start the server and open in browser:

```
http://localhost:8080/EduFee-Manager
```

---

## ✨ **Future Enhancements (Optional)**

* Add role-based dashboards
* Add payment history
* Add fee receipt generation (PDF)
* Add modern UI with Bootstrap



