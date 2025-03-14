# Agile Final Project: Sprint Planning and Execution

## **Project Overview**
This project involves developing the back-end product catalog for an e-commerce website using Agile methodologies. As the Product Owner, Scrum Master, and Developer, the tasks include creating user stories, managing a Kanban board, refining the backlog, planning sprints, and simulating a sprint execution.

---

## **GitHub Repository & Kanban Board Setup**
- **Repository Name**: `agile-final-project` (public)
- **Project Name**: `Final Project`
- **Kanban Board Columns**: 
  - Icebox  
  - Product Backlog  
  - Sprint Backlog  
  - In Progress  
  - Review/QA  
  - Done  

---

## **User Stories**
Each user story follows the format:  
**As a [user], I need [functionality] so that [business value].**

### **1. Create a Product**  
- *As an admin, I need the ability to create a product in the catalog so that new products can be added for sale.*  
- **Acceptance Criteria:**  
  - Given valid product details, when I create a product, then it should be stored in the database.

### **2. Retrieve a Product**  
- *As a customer, I need the ability to retrieve a product from the catalog so that I can view product details.*  
- **Acceptance Criteria:**  
  - Given a product ID, when I request product details, then the correct product should be returned.

### **3. Update a Product**  
- *As an admin, I need the ability to update a product in the catalog so that I can modify product details.*  
- **Acceptance Criteria:**  
  - Given a valid product ID and new details, when I update a product, then the database should reflect the changes.

### **4. Delete a Product**  
- *As an admin, I need the ability to delete a product in the catalog so that I can remove outdated or incorrect items.*  
- **Acceptance Criteria:**  
  - Given a valid product ID, when I delete a product, then it should no longer be available in the catalog.

### **5. Like a Product**  
- *As a customer, I need the ability to like a product so that I can save my favorite items.*  
- **Acceptance Criteria:**  
  - Given a product ID, when I like a product, then my preference should be recorded.

### **6. Dislike a Product**  
- *As a customer, I need the ability to dislike a product so that I can manage my preferences.*  
- **Acceptance Criteria:**  
  - Given a product ID, when I dislike a product, then my preference should be recorded.

### **7. List All Products**  
- *As a customer, I need the ability to list all products so that I can browse the catalog.*  
- **Status:** Moved to **Icebox**.

### **8. Query a Subset of Products**  
- *As a customer, I need the ability to query a subset of products so that I can filter my search.*  
- **Status:** Moved to **Icebox**.

### **9. Host on the Cloud**  
- *As a stakeholder, I need the product catalog hosted in the cloud so that it is accessible globally.*  

### **10. Automate Deployment**  
- *As a developer, I need automation to deploy new changes to the cloud so that updates are seamless.*  

---

## **Backlog Management & Sprint Planning**
- **Icebox:** Issues 7 & 8 (Lower Priority)  
- **Product Backlog:** Issues 1-6, 9-10 (Prioritized Order)  
- **Sprint Milestone:** Duration: **2 weeks**  
- **Sprint Backlog:** Issues 1-4 (Top Priority)  
- **Labels:**
  - `enhancement`: Features  
  - `technical debt`: Refactoring and improvements  
- **Story Points Assigned (Using Fibonacci Sequence):**  
  - Create: **5**, Retrieve: **3**, Update: **3**, Delete: **2**  

---

## **Sprint Execution Simulation**
1. Move **Create a product** to **In Progress** (Assign to self).  
2. Move **Create a product** to **Review/QA**, move **Retrieve a product** to **In Progress**.  
3. Move **Create a product** to **Done**, move **Retrieve a product** to **Review/QA**, move **Update a product** to **In Progress**.  
4. Move **Retrieve a product** to **Done**, move **Update a product** to **Review/QA**, move **Delete a product** to **In Progress**.  
5. Move **Update a product** to **Done**, leave **Delete a product** in **In Progress** (Sprint Ends).  

---

## **Burndown Chart & Project Completion** 
zenhub for Burnchart & report

### **License**
This project is licensed under the [MIT License](LICENSE).

---


