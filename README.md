# Student Registration Form - React State, Forms & CSS Modules

### Practical Question 2: React State, Forms, and Styling

---

## 🎯 Requirements Met
1. **`useState` Management**: State is used to store and update form inputs (`name`, `email`, `course`) as well as the list of submitted student records.
2. **Controlled Components**: Every input element binds its `value` to state and updates it via an `onChange` event handler.
3. **Fields Included**:
   - `Name` (Text input)
   - `Email` (Email input)
   - `Course` (Select dropdown / text)
4. **Display Submitted Details**: Submitted records are displayed in real-time below the registration form in styled cards.
5. **Styling**: Structured using **CSS Modules** (`StudentForm.module.css`, `SubmittedDetails.module.css`, `App.module.css`) for scoped, conflict-free styling with modern aesthetics.

---

## 📂 File Structure
```
Student Registration Form/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── main.jsx
    ├── App.jsx                              # Main container state & layout
    ├── App.module.css                       # Scoped CSS Module for App
    ├── index.css                            # Global styles and design tokens
    └── components/
        ├── StudentForm.jsx                  # Controlled Form with useState
        ├── StudentForm.module.css           # Scoped CSS Module for Form
        ├── SubmittedDetails.jsx             # Displays submitted records
        └── SubmittedDetails.module.css      # Scoped CSS Module for Records
```

---

## 🚀 How to Run the Project

1. Navigate into the folder:
   ```bash
   cd "Student Registration Form"
   ```
2. Start the Vite development server:
   ```bash
   npm run dev
   ```
3. Open `http://localhost:5173/` (or the port shown in terminal).
