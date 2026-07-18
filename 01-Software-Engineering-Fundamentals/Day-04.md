📅 Day 04 – Functional Requirements vs Non-Functional Requirements

🎯 Today's Goal 

Understand the two major types of software requirements:

- Functional Requirements (FR)
- Non-Functional Requirements (NFR)

Learn their differences, importance, real-world examples, and how they are used in software development.

---

🤔 Why Do We Need Different Types of Requirements?

Suppose a client says:

«"I want an Expense Tracker App."»

If we only write:

- Add Expense
- Delete Expense
- Search Expense

Is the project complete?

No.

The client also expects:

- The app should be fast.
- The app should be secure.
- Data should not be lost.
- The app should be easy to use.
- The app should work smoothly.

This is why software requirements are divided into two categories.

---

📖 What are Software Requirements?

Software requirements describe what a software system should do and how it should perform.

They are mainly divided into two categories.

Software Requirements
        │
        ├───────────────┐
        │               │
        ▼               ▼
 Functional       Non-Functional
 Requirements      Requirements

Both are equally important for building high-quality software.

---

📌 Functional Requirements (FR)

Definition

Functional Requirements describe what the software should do.

They define the features and functions of the software.

Simply put,

«Functional Requirements describe the functionality of the software.»

---

Examples

For an Expense Tracker App:

- User Registration
- User Login
- Add Expense
- Edit Expense
- Delete Expense
- Search Expenses
- View Monthly Report
- Export Report

These are all Functional Requirements because they describe what the application can do.

---

School Management App Example

Functional Requirements include:

- Student Login
- Teacher Login
- Attendance Management
- Homework Management
- Fee Management
- Result Management
- Notifications
- Profile Update

Each requirement represents a feature.

---

📌 Non-Functional Requirements (NFR)

Definition

Non-Functional Requirements describe how the software should perform.

They define the quality, performance, and behavior of the software.

Simply put,

«Non-Functional Requirements describe the quality of the software.»

---

Examples

For an Expense Tracker App:

- App should open within 2 seconds.
- Data should be encrypted.
- The app should work offline.
- The app should support thousands of users.
- Battery consumption should be low.
- The UI should be responsive.

These requirements improve the overall user experience.

---

📊 Functional vs Non-Functional Requirements

Functional Requirements| Non-Functional Requirements
Describe what the software does| Describe how the software performs
Focus on features| Focus on quality
Based on user actions| Based on system behavior
Easy to observe| Measured using performance and quality
Example: Login| Example: Login should complete within 2 seconds

---

🌍 Real-World Example

WhatsApp

Functional Requirements

- User Login
- Send Messages
- Receive Messages
- Voice Calls
- Video Calls
- Share Images
- Share Documents

Non-Functional Requirements

- Messages should be delivered quickly.
- Chats should be encrypted.
- App should rarely crash.
- Battery usage should be optimized.
- The app should support millions of users.

---

📱 Flutter Example

Suppose you are building a School Management App.

Functional Requirements

- Login
- Attendance
- Homework
- Results
- Notifications
- Fee Payment

Non-Functional Requirements

- App should load within 3 seconds.
- Data should remain secure.
- UI should be smooth.
- Offline mode should be available.
- Server response should be fast.
- App should work on different screen sizes.

---

📊 Common Non-Functional Requirements

⚡ Performance

The software should respond quickly.

Example:

The dashboard should load within 2 seconds.

---

🔒 Security

User data should remain protected.

Example:

Passwords should be encrypted.

---

📈 Scalability

The software should support increasing users.

Example:

The application should handle one million users.

---

🛠️ Reliability

The software should continue working without frequent failures.

Example:

System uptime should be 99.9%.

---

😊 Usability

The software should be simple and easy to use.

Example:

A new user should understand the app without training.

---

🔧 Maintainability

The software should be easy to update and improve.

Example:

Developers should be able to add new features without affecting existing functionality.

---

🌐 Availability

The software should remain available whenever users need it.

Example:

The application should be available 24×7.

---

🔄 Requirement Classification

Expense Tracker App

               Requirements
                     │
      ┌──────────────┴──────────────┐
      │                             │
      ▼                             ▼
Functional                  Non-Functional

Add Expense                 Fast

Delete Expense              Secure

Search Expense              Reliable

Monthly Report              Easy to Use

User Login                  Offline Support

---

⭐ Why Both Requirements Matter?

Imagine an app with many features but poor performance.

- It crashes frequently.
- It is very slow.
- User data is not secure.

Would users continue using it?

No.

Similarly, an app that is fast and secure but has no useful features is also unsuccessful.

A successful software product requires both Functional and Non-Functional Requirements.

---

💡 Best Practices

- Clearly separate Functional and Non-Functional Requirements.
- Document every requirement before development.
- Discuss performance expectations with the client.
- Never ignore security requirements.
- Review requirements regularly during the project.

---

⚠️ Common Beginner Mistakes

- Focusing only on features.
- Ignoring software quality.
- Forgetting security requirements.
- Ignoring scalability.
- Not documenting Non-Functional Requirements.

---

🎤 Interview Notes

Q1. What are Functional Requirements?

Answer:

Functional Requirements describe what the software should do. They define the features and functionality of the system.

---

Q2. What are Non-Functional Requirements?

Answer:

Non-Functional Requirements describe how the software should perform. They define quality attributes such as performance, security, reliability, usability, and scalability.

---

Q3. Give one example of each.

Functional Requirement

«User can reset their password.»

Non-Functional Requirement

«Password reset email should be delivered within one minute.»

---

📝 Key Takeaways

- Software requirements are divided into Functional and Non-Functional Requirements.
- Functional Requirements define software features.
- Non-Functional Requirements define software quality.
- Both are essential for successful software development.
- Ignoring Non-Functional Requirements can lead to poor user experience.

---

📚 New Terms Learned

Term| Meaning
Functional Requirement| Defines what the software should do
Non-Functional Requirement| Defines how the software should perform
Performance| Speed and responsiveness of the software
Security| Protection of user data
Scalability| Ability to support increasing users
Reliability| Ability to work without failures
Usability| Ease of using the software
Maintainability| Ease of modifying and updating the software
Availability| Time during which the software remains accessible

---

🎯 Mini Exercise

Imagine you are building a Library Management System.

Without writing any code:

Write:

- 10 Functional Requirements
- 10 Non-Functional Requirements

Try to think like a Software Engineer by considering both features and software quality.

---

💬 Quote of the Day

«"A successful software product is not only rich in features but also rich in quality."»
