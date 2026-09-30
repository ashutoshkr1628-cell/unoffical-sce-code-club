# 💻 Code Club SCE Saharsa
live link : file:///D:/code%20club%20website/about.html
A modern, responsive web platform for **Code Club – Saharsa College of Engineering (SCE)**, designed to provide students with a central place to explore coding activities, events, resources, membership, and club information.

> **Note:** This is an unofficial, student-operated project and is not an official publication of the Bihar Department of Science & Technology.

---

## 🌐 Project Overview

**Code Club SCE Saharsa** is a student-focused web platform created to support the coding and technical community at Saharsa College of Engineering.

The website provides an organized interface for students to:

* Explore Code Club activities
* Become a club member
* Generate a digital membership ID card
* Explore coding events and hackathons
* Access learning resources
* View club information
* Contact the club
* Browse frequently asked questions
* Manage and export membership information

The project focuses on creating a clean, responsive, and user-friendly experience for students.

---

## ✨ Features

### 👤 Membership Registration

Students can submit their membership information through an online registration form.

The registration form includes:

* Full Name
* Roll / Registration Number
* Branch
* Academic Year
* Email
* Phone Number
* Coding Interests
* GitHub Profile
* LinkedIn Profile
* Motivation for Joining

---

### 🪪 Digital Membership ID Card

After registration, the website provides a digital membership card containing information such as:

* Member Name
* Membership ID
* Department
* Academic Year
* Roll Number
* Issue Date
* Membership Status

The card can also be prepared for **printing or saving**.

---

### 🎯 Events & Activities

The platform can be used to showcase technical activities such as:

* Coding competitions
* Hackathons
* Workshops
* Technical sessions
* Club events
* Student activities

---

### 📚 Learning Resources

The website provides a dedicated area for students to discover useful technical and programming resources.

---

### 📞 Contact & FAQ

A dedicated contact page provides:

* Campus/location information
* Club contact information
* Meeting information
* Inquiry form
* Frequently Asked Questions

---

### 📊 Membership Management

The project is structured to support a membership management system where administrators can view:

* Total members
* Member details
* Membership IDs
* Roll numbers
* Branches
* Academic years
* Registration dates
* Membership status

The system can also support searching, filtering, and exporting member information.

---

### 📁 CSV Export

Membership information can be exported as a **CSV file**, making it easier to maintain and analyze the membership roster.

---

### 📱 Responsive Design

The website is designed to work across different screen sizes, including:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📟 Tablet

---

## 🛠️ Technologies Used

| Technology       | Purpose                         |
| ---------------- | ------------------------------- |
| HTML5            | Website structure               |
| CSS3             | Styling and layout              |
| JavaScript       | Interactivity and functionality |
| DOM Manipulation | Dynamic page updates            |
| Responsive CSS   | Mobile and tablet compatibility |
| CSV              | Membership data export          |

---

## 📂 Project Structure

```text
Code-Club-SCE-Saharsa/
│
├── index.html
├── register.html
├── contact.html
│
├── css/
│   ├── style.css
│   ├── components.css
│   ├── pages.css
│   └── responsive.css
│
├── js/
│   ├── main.js
│   └── register.js
│
├── images/
│   └── ...
│
└── README.md
```

> The exact files and folders may change as the project continues to develop.

---

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the Project

```bash
cd YOUR-REPOSITORY
```

### 3. Run the Website

You can open `index.html` directly in your browser.

For development, it is recommended to use **VS Code with Live Server** or another local development server.

---

## 📝 Membership Registration Flow

The general registration workflow is:

```text
Student
   │
   ▼
Registration Form
   │
   ▼
Input Validation
   │
   ▼
Membership ID Generation
   │
   ▼
Digital Membership Card
   │
   ▼
Success Confirmation
   │
   ▼
Membership Roster / Database
```

---

## 🪪 Membership ID

Each registered member can be assigned a unique membership ID.

Example format:

```text
SCE-CC-2026-0001
```

The exact ID-generation logic is handled by the project's JavaScript implementation and may evolve as the database system is developed.

---

## 🗃️ Planned Database Architecture

A future version of the project can use a centralized database to maintain membership information across devices.

### Suggested `members` collection/table

| Field               | Description                |
| ------------------- | -------------------------- |
| `member_id`         | Unique membership ID       |
| `name`              | Member's full name         |
| `roll_no`           | Roll / registration number |
| `branch`            | Academic branch            |
| `academic_year`     | Current academic year      |
| `email`             | Member email               |
| `phone`             | Contact number             |
| `interests`         | Coding/technical interests |
| `github`            | GitHub profile             |
| `linkedin`          | LinkedIn profile           |
| `motivation`        | Reason for joining         |
| `registration_date` | Registration date          |
| `status`            | Membership status          |
| `updated_at`        | Last update time           |

---

## 🔐 Admin Dashboard

A planned administrator dashboard can provide:

* 📊 Total member count
* 👥 Complete member list
* 🔎 Member search
* 🏷️ Branch filtering
* 📅 Academic-year filtering
* 🟢 Membership status
* 📄 Member details
* 📥 CSV export
* ✏️ Member information management

Example dashboard:

```text
+--------------------------------------+
|       CODE CLUB ADMIN DASHBOARD      |
+--------------------------------------+
|                                      |
| Total Members          128           |
| Active Members         120           |
| Pending Members          8           |
|                                      |
+--------------------------------------+
| Search Member: [______________]      |
+--------------------------------------+
| Name | Member ID | Branch | Status   |
|------|-----------|--------|----------|
| ...  | ...       | ...    | ...      |
+--------------------------------------+
```

---

## 🔒 Security Considerations

When connecting the project to a real database:

* Admin authentication should be implemented.
* Database credentials should never be placed directly in frontend JavaScript.
* Environment variables should be used for private credentials.
* Proper authorization should be applied to administrative operations.
* Sensitive member information should not be publicly exposed.
* Input validation should be performed on both client and server sides.

---

## 🎨 Design Goals

The project follows these design principles:

* Clean interface
* Simple navigation
* Student-friendly experience
* Responsive layout
* Consistent visual components
* Easy-to-understand forms
* Accessible information
* Modern technical-club presentation

---

## 🚀 Future Improvements

Possible future enhancements include:

* [ ] Centralized cloud database
* [ ] Admin authentication
* [ ] Complete members dashboard
* [ ] Real-time member count
* [ ] Member search and filtering
* [ ] Member status management
* [ ] QR code on membership cards
* [ ] Online event registration
* [ ] Event attendance tracking
* [ ] Automated email notifications
* [ ] Member profile pages
* [ ] Certificate generation
* [ ] Club announcements
* [ ] Member analytics
* [ ] Backend API integration

---

## 📸 Screenshots

Add screenshots of your project here.

### 🏠 Home Page

```text
Add your homepage screenshot here
```

### 📝 Registration Page

```text
Add your registration page screenshot here
```

### 🪪 Membership Card

```text
Add your membership card screenshot here
```

### 📅 Events Page

```text
Add your events screenshot here
```

### 📊 Admin Dashboard

```text
Add your admin dashboard screenshot here
```

---

## 💡 Why This Project?
