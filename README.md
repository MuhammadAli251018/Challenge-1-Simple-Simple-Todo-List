# Challenge #1: Simple-Simple-Todo-List

## **Objective**
Create a simple Todo List application that allows users to:
 **add**, **update**, and **delete** tasks.
 This project will introduce fundamental Android development concepts while encouraging **clean code** practices and **unit testing**.

---

## **Requirements**
### **Mandatory Features**
1. **Task Management:**
   - Add new tasks
   - Update existing tasks
   - Delete tasks
2. **Data Persistence:**
   - Use Room Database to store tasks
   - Implement ViewModel and LiveData for data handling
3. **Basic UI (Compose/XML):**
   - Simple UI with RecyclerView/LazyColumn to display tasks
   - Floating Action Button (FAB) to add tasks
   - EditText/TextField and Button for updating tasks
4. **MVVM Architecture:**
   - Implement Model-View-ViewModel (MVVM) architecture to separate concerns
5. **Error Handling & Validation:**
   - Prevent empty tasks from being added
   - Display a Toast message or Snackbar for errors

---

## **Bonus Features (Optional for Extra Points)**
1. **Task Completion:**
   - Add a checkbox to mark tasks as complete
2. **Task Categories or Priority:**
   - Implement categories (Work, Personal, etc.) or/and priority levels (High, Medium, Low)
3. **UI Enhancements:**
   - Use Material Design for improved UI
   - Implement animations or transitions
4. **Dark Mode Support**
5. **Unit Testing:**
   - Write unit tests for ViewModel and Repository and DB using Unit Tests
6. **State Handling:**
   - Use Kotlin Flows or StateFlow for better UI state management
7. **Data Backup:**
   - Implement local backup using SharedPreferences or DataStore

---

## **Best Practices (Highly Encouraged)**
- Follow **SOLID principles** and **clean architecture** (As much as you can)
- Write **clear and maintainable code** with meaningful variable names
- Use **sealed classes and enums** where applicable
- Follow **Kotlin best practices** (avoid nullable variables unless necessary)
- Document code with comments where needed

---

## **Submission & Review**
1. **Submit your project** clone this repo and add README.md explaining:
   - Project overview
   - Features implemented
   - Additional features (if any)
   - How to run the app

---

## **Points System**
- **Mandatory Features Completed:** +10 points
- **Bonus Features:** +5 points each
- **Following Clean Code & Architecture:** +5 points
- **Unit Tests:** +5 points
- **Active Code Review Participation:** +3 points
