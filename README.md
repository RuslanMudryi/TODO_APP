# React Todo App

This project is a **Todo application** built using **React** and an **external API**.  
The app allows users to manage a list of tasks (**todos**) with features such as **adding, deleting, toggling status, and editing task titles**.  

## 🚀 Key Features  

### ✅ Adding a New Todo  
- Users can add a new task via an **input form**.  
- After successful addition, the todo appears in the list.  

### ❌ Deleting a Todo  
- Each task can be **deleted** using the **"×"** button.  
- After successful deletion, the todo is removed from the list.  

### 🔄 Toggling Todo Status  
- Users can **change the status** of a task (**completed/not completed**) using a checkbox.  
- While waiting for the API response, the todo is **covered with a loader overlay**.  
- If an error occurs during status update, an **error notification** is displayed.  

### 🔘 Toggling Status for All Todos  
- The **"Toggle All"** button allows **changing the status of all tasks** to the opposite.  
- The button is **active only when all tasks are completed**.  
- API requests are **sent only for tasks whose status has actually changed**.  

### ✏️ Editing a Todo Title  
- Users can **edit the title** of a task by **double-clicking** on it.  
- During editing, an **input field replaces** the title and delete button.  
- Changes are **saved** on form submission (**pressing Enter**) or when the input field **loses focus** (**onBlur**).  
- If the new title is **the same as the old one**, editing is **canceled**.  
- **Pressing Esc cancels editing**.  
- If the **new title is empty**, the todo is **deleted** (same as the **"×"** button).  
- While waiting for the API response, the todo is **covered with a loader overlay**.  
- If the title is **successfully updated**, the todo **is refreshed**.  
- If an **error occurs** during update or deletion, an **error message is displayed**.  

## 🛠️ Technologies Used  

- **React** – A JavaScript library for building user interfaces.  
- **TypeScript** – A typed superset of JavaScript for better code quality and maintainability.  
- **API Integration** – Fetching and updating data from an external API.  
- **Cypress** – End-to-end testing framework to ensure the app works as expected.  
- **Prettier** – Code formatting tool for maintaining a consistent code style.  
- **SCSS** – A powerful and maintainable CSS preprocessor for styling. 

## Demo

[DEMO link](https://RuslanMduryi.github.io/TODO-APP/) 
