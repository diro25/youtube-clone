# ✅ To-Do List App

> A lightweight, colourful task manager built with vanilla **HTML**, **CSS**, and **JavaScript**.

[![HTML](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-Not%20specified-lightgrey)](#license)

## ✨ Intended experience

Keep everyday work visible and simple. The interface is designed to start with a few example tasks and offer a focused way to add, complete, edit, and remove tasks.

| Feature           | Description                                                 |
| ----------------- | ----------------------------------------------------------- |
| ➕ Add tasks      | Type a task and select **+ Add** to place it in your list.  |
| ☑️ Complete tasks | Use the checkbox to mark an item as finished.               |
| ✏️ Edit tasks     | Hover a task and select the pencil icon to change its text. |
| 🗑️ Delete tasks   | Hover a task and select the bin icon to remove it.          |
| 📊 Live stats     | See active, completed, and total task counts at a glance.   |

## 🧰 Built with

- **HTML5** — page structure and accessible native controls
- **CSS3** — the purple, card-based interface and hover interactions
- **JavaScript** — task creation, editing, completion, deletion, and statistics

No frameworks, package manager, build step, or server are required.

## 🚀 Run it locally

1. Clone or download this repository.

   ```bash
   git clone <your-repository-url>
   ```

2. Open the project folder.

   ```bash
   cd to-do-app
   ```

3. Open `index.html` in any modern web browser.

That’s it—there are no dependencies to install.

## 🎯 How to use it

Once the current page wiring is corrected (see [Current implementation status](#-current-implementation-status)), the intended flow is:

1. Enter a task in the **“Add a new task…”** field.
2. Click **+ Add**.
3. Tick a checkbox when you finish a task.
4. Hover over a task to reveal its edit and delete controls.
5. Watch the statistics cards update as your list changes.

## 📁 Project structure

```text
to-do-app/
├── index.html                       # App markup and current in-page behaviour
├── style.css                        # Reusable visual styles
├── script.js                        # Standalone task-adding logic
├── circle-check-regular-full.svg    # Checkmark icon asset
└── README.md                        # Project documentation
```

## 🔍 Current implementation status

- `index.html` contains the page layout and its current in-page task logic.
- `style.css` and `script.js` are present as separate files, but are not currently linked from `index.html`.
- The in-page script refers to `taskList`, while the page markup currently uses `taskLists`; this prevents the startup task list from loading until the IDs match.
- The intended task data is session-only: no database or browser storage is implemented.

## 💡 Ideas for the next version

- Save tasks with `localStorage` so they remain after a refresh.
- Add keyboard support, such as pressing <kbd>Enter</kbd> to add a task.
- Add due dates, priorities, categories, and search/filter controls.
- Improve small-screen/mobile interactions.
- Add automated tests and a live deployment.

## 🤝 Contributing

Contributions are welcome. A simple workflow:

1. Fork the project and create a feature branch.
2. Make one focused improvement.
3. Test it in a browser.
4. Open a pull request describing what changed.

## 📄 License

No license has been specified yet. Add a license file before reusing or distributing this project under defined terms.

---

Made for staying focused, one task at a time. ✨
