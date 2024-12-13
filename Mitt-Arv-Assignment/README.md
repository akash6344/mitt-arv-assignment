# Kanban Board

This project is a simple Kanban board implemented using ReactJS. It allows users to manage tasks across different stages: To Do, In Progress, Peer Review, and Done. The board supports drag-and-drop functionality for task movement and a search box to filter tasks by title.

## Features
- Four columns representing task stages: To Do, In Progress, Peer Review, and Done.
- Task cards displaying task title and description.
- Drag-and-drop functionality to move tasks between columns.
- Search bar to filter tasks by title.
- Floating button to add new tasks (currently supports adding tasks to the To Do column only).

## Setup and Run the Application
1. Clone the repository:
2. Navigate to the project directory:
3. Install dependencies:
4. Start the development server:
5. Open your browser and navigate to `http://localhost:3000` to see the Kanban board in action.

## Technologies Used
- ReactJS
- CSS

## Folder Structure
- `src`
- `components`
 - `TaskBoard.js`: Main component that manages the state of the tasks and renders the columns.
 - `TaskColumn.js`: Component representing each column in the Kanban board.
 - `TaskCard.js`: Component representing each task card.
- `App.js`: Root component that renders the `TaskBoard`.
- `index.js`: Entry point of the application.
- `styles.css`: CSS file for styling the components.

## Best Practices Followed
- Consistent coding practices.
- Meaningful variable names and comments.
- Responsive UI.
- Clear and organized folder structure.

## License
This project is licensed under the MIT License.
