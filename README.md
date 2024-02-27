  # Prajwal-Todo-List

a-  Todo List Web Application: This project is a web application for managing todo lists.

b-  React-based Frontend: The frontend of the application is built using React, a popular JavaScript library for building user interfaces.

c-  State Management: React's useState hook is used for managing state within the components. State is utilized to manage the title, description, and the list of main tasks.

d-  Form Submission Handling: Form submission is handled through the submitHandler function. When the form is submitted, it prevents the default behavior, adds the new task to the mainTask state array, clears the input fields for title and description, and logs the updated mainTask array to the console.

e-  Task Deletion: Task deletion functionality is implemented through the deleteHandler function. When the delete button associated with a task is clicked, it removes the corresponding task from the mainTask array using the index of the task.

f-  Conditional Rendering: The UI is dynamically rendered based on the length of the mainTask array. If there are no tasks, a message indicating "No Task Available" is displayed. Otherwise, each task is rendered as a list item along with a delete button.
