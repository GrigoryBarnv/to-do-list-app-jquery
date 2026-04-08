# To-Do List App (jQuery)

A simple to-do list built with HTML, CSS, JavaScript, and jQuery UI. It lets you add tasks, mark them as completed, remove them, and drag items to reorder the list.

## Features

- Add new tasks from the input field
- Double-click a task to mark it as completed
- Click `X` to remove a task
- Drag and drop tasks to reorder them
- Clean, lightweight single-page layout

## Tech Stack

- HTML5
- CSS3
- JavaScript
- jQuery
- jQuery UI (`sortable`)

## Project Structure

```text
.
|-- index.html
|-- scripts.js
|-- styles.css
|-- README.md
```

## How To Run

1. Clone or download this folder.
2. Open `index.html` in your browser.

If you want a smoother local-development workflow, you can also serve the folder with a small local server, for example:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## How It Works

- Type a task into the input box
- Click the `Add` button
- Double-click a list item to toggle the completed style
- Click the `X` on the right side of an item to hide/delete it
- Drag items to change their order

## Notes

- The app uses jQuery from a CDN, so an internet connection is needed unless those dependencies are hosted locally.
- In the current project layout, `index.html` references `./js/scripts.js`, but the actual script file in this directory is `scripts.js`. If the app logic does not load in the browser, update that script path.

## Possible Improvements

- Submit tasks by pressing `Enter`
- Save tasks with `localStorage`
- Improve accessibility for keyboard users
- Add edit-in-place support for tasks
- Replace the inline `onclick` handler with a JavaScript event listener

## Screenshot Idea

If you want, a project screenshot or animated preview can be added here later to make the README more polished.

