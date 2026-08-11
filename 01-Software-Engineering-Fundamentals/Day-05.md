# 📅 Day 05 – Software Development Models

## 🎯 Learning Objectives

By the end of this chapter, you should understand:

* What a Software Development Model is
* Why development models are needed
* How different models organize software development
* Waterfall Model
* Prototype Model
* Iterative Model
* Incremental Model
* When different models are useful
* Advantages and disadvantages of each model

---

# 🤔 Why Do We Need Software Development Models?

Suppose a company wants to build a large application.

They have:

* Developers
* Designers
* Testers
* Project Managers
* Clients

If everyone starts working randomly, the project can become chaotic.

For example:

```text
Developer → starts coding
Designer  → changes UI
Client    → changes requirements
Tester    → finds problems
Developer → rewrites code
Client    → requests another change
```

This can lead to:

* Wasted time
* Increased cost
* Confusion
* Poor communication
* Delayed delivery
* More bugs

Therefore, software teams need a **structured development approach**.

This approach is provided by Software Development Models.

---

# 📖 What is a Software Development Model?

A **Software Development Model** is a structured approach that defines how different activities of software development will be organized and performed.

In simple words:

> **A Software Development Model is a plan for how a software project will move from requirements to a working product.**

Different projects have different requirements.

Therefore, one development model cannot be perfect for every project.

---

# 🧠 SDLC vs Software Development Model

These two concepts are related but not exactly the same.

### SDLC

SDLC describes the **general phases** involved in software development.

```text
Planning
   ↓
Requirements
   ↓
Design
   ↓
Development
   ↓
Testing
   ↓
Deployment
   ↓
Maintenance
```

### Development Model

A development model describes **how these phases are organized and executed**.

For example:

```text
Waterfall

Requirements
     ↓
Design
     ↓
Development
     ↓
Testing
```

While:

```text
Iterative Model

Version 1
   ↓
Feedback
   ↓
Version 2
   ↓
Feedback
   ↓
Version 3
```

So:

> **SDLC tells us WHAT phases exist. Development Models tell us HOW those phases are organized.**

---

# 🏗️ Major Software Development Models

Some important development models are:

```text
Software Development Models
│
├── Waterfall Model
├── Prototype Model
├── Iterative Model
├── Incremental Model
├── Spiral Model
└── Agile Model
```

We will study these models carefully.

---

# 1️⃣ Waterfall Model

## 📖 What is Waterfall Model?

The Waterfall Model is a **sequential software development model** where development moves through predefined phases in a mostly linear order.

The output of one phase becomes the input for the next phase.

---

# 🌊 Waterfall Visualization

```text
Requirements
     │
     ▼
System Design
     │
     ▼
Development
     │
     ▼
Testing
     │
     ▼
Deployment
     │
     ▼
Maintenance
```

The process flows downward like a waterfall.

That's why it is called the **Waterfall Model**.

---

# 🏗️ Example

Suppose a government organization wants a software system with:

* Clearly defined requirements
* Fixed scope
* Strict documentation
* Formal approval processes

If the requirements are unlikely to change, Waterfall can be suitable.

---

# ✅ Advantages of Waterfall

* Simple to understand
* Easy to manage
* Clear phases
* Strong documentation
* Easy to track progress
* Suitable when requirements are stable

---

# ❌ Disadvantages of Waterfall

* Difficult to handle changing requirements
* Testing happens relatively late
* Working software may appear late
* Changes can become expensive
* Customer feedback may come late

---

# 🧠 When is Waterfall Suitable?

Waterfall is more suitable when:

* Requirements are well understood.
* Requirements are unlikely to change.
* The project has strict processes.
* Documentation is very important.
* The technology is well understood.

---

# 2️⃣ Prototype Model

## 📖 What is Prototype Model?

In the Prototype Model, developers create an **early version or prototype** of the software to understand requirements and gather feedback.

The prototype may not be the final product.

It is mainly used to clarify what the user actually wants.

---

# 🔄 Prototype Flow

```text
Initial Requirements
        ↓
     Prototype
        ↓
   User Feedback
        ↓
Requirement Changes
        ↓
Final Development
```

---

# 🌍 Real-World Example

Suppose a client says:

> "I want a modern school app."

But they don't know exactly how the screens should work.

You create a prototype containing:

```text
Login
  ↓
Dashboard
  ↓
Attendance
  ↓
Result
```

The client sees it and says:

> "Dashboard me fees ka option bhi chahiye."

Now you understand the requirement better.

---

# ✅ Advantages

* Helps understand unclear requirements
* Early user feedback
* Reduces misunderstanding
* Useful for UI-heavy applications

---

# ❌ Disadvantages

* Prototype can create unrealistic expectations
* Extra time may be required
* Poorly designed prototypes may influence final design unnecessarily

---

# 3️⃣ Iterative Model

## 📖 What is Iterative Development?

In the Iterative Model, software is developed through repeated cycles called **iterations**.

Each iteration improves the previous version.

---

# 🔄 Iterative Flow

```text
Plan
 ↓
Design
 ↓
Develop
 ↓
Test
 ↓
Feedback
 ↓
Improve
 ↺
```

The cycle repeats.

---

# 🌍 Example

Suppose you are building an Expense Tracker.

### Iteration 1

```text
Add Expense
View Expense
```

### Iteration 2

```text
Add Expense
View Expense
+
Delete Expense
+
Edit Expense
```

### Iteration 3

```text
Everything above
+
Search
+
Monthly Reports
```

The software keeps improving through iterations.

---

# ✅ Advantages

* Continuous improvement
* Early working versions
* Feedback can be incorporated
* Problems can be discovered earlier

---

# ❌ Disadvantages

* Requires good planning
* Repeated changes can increase complexity
* Project scope may grow

---

# 4️⃣ Incremental Model

## 📖 What is Incremental Development?

In Incremental Development, the software is divided into smaller **functional increments**.

Each increment adds new functionality to the product.

---

# 📦 Visualization

```text
Increment 1
    ↓
Login
    ↓
Working Product

Increment 2
    ↓
Attendance
    ↓
More Complete Product

Increment 3
    ↓
Fees
    ↓
More Complete Product

Increment 4
    ↓
Reports
    ↓
Final Product
```

Each increment adds a new part of the system.

---

# 🌍 Example

School Management App:

### Increment 1

```text
Login + User Profile
```

### Increment 2

```text
Login + Profile + Attendance
```

### Increment 3

```text
Previous Features + Homework
```

### Increment 4

```text
Previous Features + Fees + Reports
```

The application becomes more complete with each increment.

---

# 🔄 Iterative vs Incremental

These concepts are often confused.

### Iterative

Focus:

> **Improve what already exists.**

```text
Version 1
   ↓
Improve
   ↓
Version 2
   ↓
Improve
   ↓
Version 3
```

### Incremental

Focus:

> **Add new functionality.**

```text
Login
  ↓
Login + Attendance
  ↓
Login + Attendance + Fees
```

In real projects, both approaches can be combined.

---

# 📊 Model Comparison

| Model       | Main Idea                      | Best When                            |
| ----------- | ------------------------------ | ------------------------------------ |
| Waterfall   | Sequential phases              | Requirements are stable              |
| Prototype   | Build early model              | Requirements are unclear             |
| Iterative   | Improve repeatedly             | Product needs gradual refinement     |
| Incremental | Add functionality step-by-step | Product can be divided into features |

---

# 🌍 Real-World Scenario

Imagine you want to build a **Food Delivery App**.

Requirements are unclear:

> "Make something like Zomato."

A Prototype Model could help first.

You create:

```text
Home
 ↓
Restaurant
 ↓
Menu
 ↓
Cart
```

Client gives feedback.

Then development begins.

For another project, suppose the government gives you a fixed specification that is unlikely to change.

Waterfall may be more appropriate.

---

# 🧠 Important Concept

There is no universally "best" Software Development Model.

The correct model depends on:

* Project type
* Requirement stability
* Risk
* Customer involvement
* Project size
* Team structure
* Delivery expectations
* Technology

A good Software Engineer chooses the approach based on the project instead of blindly following one model.

---

# 💡 Best Practices

* Understand project requirements before selecting a model.
* Consider how frequently requirements may change.
* Consider customer involvement.
* Consider project risk.
* Select the model that fits the project.
* Do not choose a model simply because it is popular.

---

# ⚠️ Common Beginner Mistakes

### Mistake 1

Thinking Waterfall means "never change anything."

**Reality:** Changes can happen, but handling them may be difficult and expensive.

### Mistake 2

Thinking Prototype = final product.

**Reality:** A prototype is primarily used to explore and clarify requirements.

### Mistake 3

Confusing Iterative and Incremental development.

**Remember:**

```text
Iterative   → Improve
Incremental → Add
```

---

# 🎤 Interview Notes

## Q1. What is a Software Development Model?

A Software Development Model is a structured approach that defines how software development activities are organized and performed.

---

## Q2. What is Waterfall Model?

Waterfall is a sequential development model in which software development phases are generally completed one after another.

---

## Q3. What is a Prototype?

A prototype is an early version or representation of a software product used to understand requirements and obtain user feedback.

---

## Q4. Difference between Iterative and Incremental?

**Iterative development** focuses on repeatedly improving existing functionality.

**Incremental development** focuses on adding new functionality in separate increments.

---

# 📝 Quick Revision

```text
Waterfall
→ Sequential

Prototype
→ Understand unclear requirements

Iterative
→ Improve repeatedly

Incremental
→ Add functionality step-by-step
```

---

# 📚 Glossary

| Term              | Meaning                                        |
| ----------------- | ---------------------------------------------- |
| Development Model | Approach used to organize software development |
| Waterfall         | Sequential development approach                |
| Prototype         | Early version used to clarify requirements     |
| Iteration         | Repeated development cycle                     |
| Increment         | A functional addition to the product           |
| Feedback          | Information provided to improve the product    |
| Sequential        | One phase generally follows another            |

---

# 🎯 Mini Challenge

Imagine a client gives you these two projects:

### Project A

A government system with:

* Fixed requirements
* Strict documentation
* Very few expected changes

### Project B

A startup app with:

* Unclear requirements
* Frequent customer feedback
* New features every few weeks

### Your Task

Choose a suitable development model for each project.

Then explain **WHY** you selected it.

Do not just memorize the answer.

Think like a Software Engineer.

---

# 🔗 Connection With Previous Days

```text
Day 01
Software Engineering
        ↓
Day 02
SDLC
        ↓
Day 03
Requirement Engineering
        ↓
Day 04
Functional & Non-Functional Requirements
        ↓
Day 05
Software Development Models
```

We are gradually moving from:

**"What is Software Engineering?"**

to:

**"How should we actually organize software development?"**

---

# 🚀 Next Topic

**Day 06 – Software Development Models: Spiral & Agile**

We will continue with more advanced models and especially understand why **Agile became extremely important in modern software development.**
---

# 📍 Repository Location

```text
software-engineering-handbook/
└── 01-Software-Engineering-Fundamentals/
    └── Day-05.md
```
