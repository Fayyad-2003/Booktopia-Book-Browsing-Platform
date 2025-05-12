# Booktopia 📚 

A modern and user-friendly platform where users can **explore** and **discover** books. This app allows users to **browse** top-rated, popular, and best-selling books, **search** for books, and **manage** their favorite list. All UI components, including **modals**, **sliders**, **filter bars**, and **theme switching**, were implemented manually. The app is thoroughly tested using **React Testing Library**.

---

## Table of Contents 📑  
1. [Demo](#demo-)
2. [Features](#features-)
3. [Tech Stack](#tech-stack-)
4. [Testing](#testing-)
5. [Project Structure](#complete-project-structure-) 

---

## Demo 🌐

Check out the live demo: [Live Demo](https://bookstopia.netlify.app/)

---

## Features ✨  
1. **Browse Books**  
   - Explore **top-rated**, **popular**, and **best-selling** books displayed in sliders. 🎡  
   - Browse new books with a clean and responsive **UI**. 📚  

2. **Search Books**  
   - Search by **title**, **category**, or **author name**. 🔍  
   - Paginated results for easy navigation.  

3. **Filter and Sort**  
   - Filter by **publish date** or **rating**. 🗓️⭐  
   - Sort in **ascending/descending** order. 🔄  

4. **Book Details**  
   - View details in a **modal** with similar books. 📖  

5. **Favorite List**  
   - Save books to **local storage**. ❤️  

6. **Theme Switching**  
   - Toggle between **light/dark** themes. 🌞🌙  

7. **Custom UI**  
   - No external libraries — built from scratch. 🛠️  

8. **Testing**  
   - Fully tested with **React Testing Library**. ⚗️  

---

## Tech Stack 🛠️  

| **Category**       | **Technologies & Tools**                          |
|--------------------|--------------------------------------------------|
| **Frontend**       | React, React Router, Context API (+ useReducer)  |
| **Styling**        | CSS (No external UI libraries)                   |
| **Testing**        | React Testing Library                            |
| **State Management**| Custom Context API + Reducer Pattern            |
| **Deployment**     | Netlify                                         |
| **Version Control**| Git & GitHub                                    |

---

## Testing 🧪
To run the test suite for this project:


1. **Clone the repository**:
   ```bash
   git clone https://github.com/Fayyad-2003/Booktopia-Book-Browsing-Platform.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Booktopia-Book-Browsing-Platform
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Run all tests**:
   ```bash
   npm test
   ```
5. **Test specific components**:
   ```bash
   npm test src/components/ComponentName.test.js
   ```
---

## Complete Project Structure 📂  
```text
booktopia/
├── public/
│   ├── icon.svg
│   └── index.html
├── src/
│   ├── assets/
│   ├── components/
│   ├── data/
│   ├── hooks/
│   ├── pages/
│   ├── router/
│   ├── ui/
│   ├── utils/
│   ├── App.jsx
│   └── index.js
└── README.md
```