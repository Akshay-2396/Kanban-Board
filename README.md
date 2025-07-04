
# 🧾 Kanban Board Task Management App
📕 **Project Overview**

This project implements a Kanban-style task management application using React JS. The application allows users to create, organize, and move tasks between columns such as To Do, In Progress, and Done. It utilizes drag-and-drop functionality, state management with React's Context API, and local storage for persistence, ensuring that user data is maintained even after page refreshes.

# ✅ Features
**Task Board Layout:**

* Multiple columns: To Do, In Progress, and Done.

* Each column displays task cards with:

* Title, Description, Optional Tags, Priority, and Deadline.

* Task cards color changes based on column. 

**Add/Edit/Delete Tasks:**

* Create new tasks via a form input (task name, description, status).

* Edit and delete tasks by clicking on them.

* Alert will pop up if the form is left empty while adding a task.

**Drag and Drop:**

* Tasks can be moved between columns with a drag handle.

* Task priority and deadline impact the layout and order of cards automatically.

* Columns have separate colors, and task cards adjust color based on the column and status.

**Task Details Modal:**

* Clicking a task opens a modal to view and edit the full task details.

* Inline editing for fields like description or status.

**Persistence:**

* Task data is stored in localStorage, ensuring data persists after page refresh.

🤷‍♂️ **User Features:**

* View tasks organized into columns.

* Drag-and-drop functionality for task reorganization.

* Ability to create, edit, or delete tasks.

* Data persists locally (tasks won't be lost on page reload).

* Optional tags, priorities, and deadlines for tasks.

* Responsive layout using TailwindCSS.

# 🛠 Tech Stack
* React JS (for building the UI)

* TailwindCSS (for styling)

* React Hooks (useState, useContext, useEffect) for state management

* Context API (for global task state)

* dnd-kit (for drag-and-drop functionality)

* localStorage (for task persistence)


## 🚀 Deployment

 - https://kanbantoboard.netlify.app/


