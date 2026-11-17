# To Do List Application (jQuery)

A simple To Do List web app built with HTML, CSS and jQuery. Add tasks, mark them as done, or delete them, with smooth fade animations.

## Features

- Add a task by typing it and pressing **Enter**
- Empty tasks are ignored
- Mark a task as done with the **check** icon (it moves to the "Done" list)
- Delete a task with the **trash** icon
- Smooth fade-out and fade-in animations
- No build tools required

## Tech Stack

- HTML5
- CSS3
- jQuery 3.7.1
- Font Awesome 5 (icons)


## How It Works

1. jQuery listens for the `keyup` event on the input box.
2. When Enter (key code 13) is pressed and the input is not empty, a new task is created.
3. The task gets a trash icon and a check icon, each with its own click handler.
4. The task is added to the "Still to do" section and the input is cleared.
5. Clicking the trash icon fades the task out and removes it.
6. Clicking the check icon moves the task to the "Done" section.

## Future Improvements

- Save tasks with `localStorage`
- Edit existing tasks
- Add a task counter
- Dark mode
