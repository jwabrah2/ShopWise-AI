# ShopWise-AI

ShopWise-AI is a smart online shopping web application built using ASP.NET Core MVC.  
The system helps users search for products, compare options, and receive simple AI-based suggestions to support better purchasing decisions.

> This project is developed as an academic project for the Software Development and Documentation course.

---

## 1. Problem Statement

Online shoppers often struggle to find suitable products quickly.  
They have to search in many places, read long descriptions, and compare items manually.  
Most small or traditional e-commerce websites only provide a basic search box and simple category filters.  
They do not offer intelligent assistance, personalized suggestions, or explanations that match the user’s real needs.

Because of this, users spend more time searching, become confused between many options, and may even leave the website without buying anything.

---

## 2. Business Case

ShopWise-AI aims to improve the online shopping experience by providing a simple but smart platform.  
The system combines a traditional product catalog with basic AI features, such as:

- Interpreting natural language queries (for example: “laptop for programming”).
- Suggesting related products and categories.
- Helping the user narrow down choices based on simple preferences.

For a business, this can:

- Increase user engagement and satisfaction.
- Reduce the time users need to find suitable products.
- Increase the possibility of completing a purchase.
- Provide a foundation that can later be extended with real product data and more advanced AI models.

Because the system is built using ASP.NET Core MVC and an in-memory database, it is easy to develop, test, and demonstrate in an academic environment.

---

## 3. Project Scope

### In Scope

- ASP.NET Core MVC web application.
- Basic product model (id, title, brand, category).
- Simple user model (id, name, email, password, role).
- Product search and filter page.
- AI-assisted search:
  - Expanding user keywords.
  - Suggesting categories and example queries.
- Simple recommendation logic based on the current search.
- REST API endpoint for login (for example: `/api/auth/login`).
- In-memory database with sample data (no external DB).
- Basic documentation:
  - Problem statement
  - Business case
  - Scope
  - Goals
  - SDLC model, use cases, and diagrams (in separate documents).

### Out of Scope

- Real online payment integration.
- Order shipment and delivery tracking.
- Complete inventory management.
- Advanced AI model training.
- Mobile application.

---

## 4. Goals

### Main Goals

1. Build a simple and clear online shopping system using ASP.NET Core MVC.
2. Help users search for products and discover alternatives more easily.
3. Integrate basic AI-style assistance to support decision making.
4. Provide a clean and understandable code structure suitable for teaching and documentation.
5. Demonstrate how to combine MVC pages with simple REST APIs in one project.

### Secondary Goals

- Practice using GitHub for version control and collaboration.
- Apply software engineering concepts such as SDLC, requirements, and modeling.
- Prepare documentation (SRS, diagrams, Gantt chart, UI mockups) according to course requirements.

---

## 5. Technologies

- ASP.NET Core MVC (.NET 8)
- C#
- Entity Framework Core (InMemory)
- HTML / CSS / Bootstrap (for the UI)
- GitHub for source control and documentation

---

## 6. Team

- **Student:** Abdullah Ahmad Aljawabreh  
- **Role:** Developer, Analyst, and Tester  
- **Course:** Software Development and Documentation  
