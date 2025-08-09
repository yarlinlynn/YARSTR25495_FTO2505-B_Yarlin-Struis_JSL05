# Kanban – Task Management Made Simple

A sleek, responsive Kanban board built with **Tailwind CSS** and semantic HTML. This is a challenge project aimed at progressing from a static UI to a fully interactive task management app using JavaScript.

## 📸 Screenshots

![Figma Design for Challenge 5](<assets/design /JSL05 challenge.png>)


This project involves developing a **visually accurate and fully responsive Kanban board** that aligns with the provided **Figma design**. The board should be structured into multiple columns and include task cards, a static side panel, and a well-defined theme to ensure a **professional and polished user experience.**

<br/>

### JSL01 Challenge Key Objectives:

#### Logic & User Interaction

- [x] Implement a **favicon and page title** that match the application’s theme for a professional look.
- [x] Create a **Kanban board with multiple columns** (e.g., "To Do", "In Progress", "Done") that **exactly replicates** the Figma design layout.
- [x] Ensure the **board’s layout, colours, typography, and spacing** strictly follow the Figma specifications for visual consistency.
- [x] Develop a **fully responsive** board that adapts seamlessly to **both laptops and mobile devices**, mirroring the Figma design’s responsive behavior.
- [x] Display **tasks as individual cards** within their respective columns, ensuring their design (borders, shadows, padding) follows the Figma guidelines for clarity and appeal.
- [x] Include **titles on all task cards** to provide clear task descriptions.
- [x] Implement a **static side panel (in desktop view)** with the correct **icons, text, and branding elements** as per the Figma layout for a structured and professional appearance.

<br/>

### JSL02 Challenge Key Objectives:

#### Logic & User Interaction

- [x] Ensure the JavaScript file is correctly linked to the HTML document.
- [x] Prompt the user to enter details (title, description, status) for two separate tasks and store them in variables.
- [x] Convert all status inputs to lowercase automatically for consistency.
- [x] Validate the status input to allow only "todo", "doing", or "done" and repeatedly prompt the user until a valid status is entered.
- [x] Display the title and status of completed tasks (status: "done") in the console.
- [x] If no tasks are marked as "done", show a motivational message in the console: "No tasks completed, let's get to work!".

<br/>

### JSL03 Challenge Key Objectives:

#### Logic & User Interaction

- [x] Store tasks as **objects inside an array** for structured data management.
- [x] Allow users to **add up to three new tasks** to the existing task list.
- [x] Ensure each new task has a **unique incremental ID** based on the last task in the array.
- [x] Prompt users to enter **task details (title, description, status)** and store them in an object.
- [x] Alert users when they reach the task limit with the message:
  _"There are enough tasks on your board, please check them in the console."_
  Implement a **filter function** to display only tasks with the status `"done"`.
- [x] Log **all tasks** in the console with a clear label for easy review.
- [x] Log **only completed tasks** (status: `"done"`) in the console under a "Completed Tasks" label for quick reference.

##### Code Quality & Maintainability

- [x] Use meaningful variable and function names to ensure readability and maintainability.
- [x] Follow consistent indentation and formatting to enhance code clarity.
- [x] Include comments explaining key logic and functionality to support future modifications.

### JSL04 Challenge Key Objects:

##### Dynamic Task Display & Interaction
- [x] Dynamically generate task elements from the given initial data and insert them into the DOM.
- [x] Ensure tasks are placed in the correct columns ("To Do", "In Progress", "Done") based on their status.
- [x] Clicking a task should open a modal displaying its details.
**The modal should include**:
- [x] Editable input fields for the task title and description.
- [x] A select dropdown showing the current status with other status options available.
- [x] A close button that allows users to exit the modal easily.
 

##### Design & Responsiveness
- [x] Ensure the modal matches the Figma design, including a backdrop effect for focus.
- [x] Implement a fully responsive modal that works on both desktop and mobile devices.
 

##### Code Structure & Maintainability
- [x] Structure JavaScript using modular, single-responsibility functions.
- [x] Use descriptive and meaningful variable and function names for clarity.
- [x] Add JSDoc comments to major functions, describing their purpose, parameters, and return values for better documentation.

<br/>

### JSL05 Challenge Key Objects:

##### Persistent Task Storage & Retrieval
- [x] Save tasks to local storage: On page load, the application should load tasks from local storage so that the latest task list is available, even after a refresh.
- [x] Ensure that tasks are saved in local storage every time a new task is added so that tasks persist after the page refreshes.
- [x] Load tasks from local storage on startup, so users can see the latest tasks without manually re-entering them.
- [x] Tasks should be categorized correctly into their respective columns (e.g., "To Do", "Doing", "Done") based on their status when loaded from local storage.

##### Task Creation & Modal Interaction
- [x] Provide an "Add Task" button that, when clicked, opens a modal for creating a new task.
The modal should include:
- [x] Fields for entering the task title and description.
- [x] A dropdown to select the task status ("To Do", "Doing", "Done").
- [x] A submit button to add the new task to the task board immediately.
- [x] After submitting, the task should appear on the board without requiring a page refresh.

##### Design & Responsiveness
- [x] The "Add New Task" modal should match the Figma design, including mobile-responsive behavior.
- [x] Ensure that the modal and task board are fully responsive and function properly on both desktop and mobile devices.
- [x] The "Add Task" button should transform appropriately on mobile devices to match the Figma design.

##### Code Structure & Maintainability
- [x] Modularize your JavaScript code: Break your code into separate modules, each handling a single responsibility (e.g., local storage handling, task rendering, modal management).
- [x] Use descriptive variable and function names to ensure the code is clear and easy to maintain.
- [x] Include JSDoc comments for every major function and module to describe their functionality, parameters, and return values.

<br/>

### Setup Instructions

To run the project locally:

1. Clone the repository
```
git clone https://github.com/YARSTR25495_FTO2505-B_Yarlin-Struis_JSL01.git
```
2. Install dependencies
```
yarlinlynn@Yarlins-MacBook-Air YARSTR25495_FTO2505-B_Yarlin-Struis_JSL01 % npm list tailwindcss
YARSTR25495_FTO2505-B_Yarlin-Struis_JSL01@ /Users/yarlinlynn/Downloads/YARSTR25495_FTO2505-B_Yarlin-Struis_JSL01
└── (empty)

yarlinlynn@Yarlins-MacBook-Air YARSTR25495_FTO2505-B_Yarlin-Struis_JSL01 % npm install -D tailwindcss
```
3. Watch Tailwind for changes
```
npm run watch
```

<br/>

###  File structure
```
├── index.html                     ← Main HTML entry point
├── README.md                      ← Project documentation
├── tailwind.config.js             ← Tailwind CSS config
├── dist/
│   └── style.css                  ← Compiled CSS output (from Tailwind)
├── src/
│   ├── styles/
│   │   └── input.css              ← Tailwind directives (@tailwind base, etc.)
│   └── js/
│       └── script.js              ← JavaScript logic for interactivity
├── assets/
│   └── js/
│       └── script.js
```

<br/>

### License
This project is for educational use only.

<br/>

### Credits
Design provided by **CodeSpace** via [Figma Reference File](https://www.figma.com/design/y7bFCUYL5ZHfPeojACBXg2/Challenges-%7C-JSL?node-id=6033-11092&t=XbQhBWPYxXDAqp3x-1)