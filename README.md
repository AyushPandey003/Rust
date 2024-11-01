# Simple Todo App in Rust

This project is a simple command-line based Todo application built using Rust. It helps you manage your daily tasks by allowing you to add, view, and remove tasks efficiently.

## Features

- **Add Tasks**: Add a new task to your todo list.
- **View Tasks**: View all your tasks.
- **Remove Tasks**: Remove a task from your todo list by its index.

## Getting Started

### Prerequisites

Ensure you have Rust installed on your system. If not, you can install Rust using [rustup](https://rustup.rs/).

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/rust-todo-app.git
    cd rust-todo-app
    ```

2. **Build the project:**
    ```sh
    cargo build
    ```

3. **Run the application:**
    ```sh
    cargo run
    ```

## Usage

### Add a Task
To add a task, use the following command:
```sh
cargo run add "Your new task"
View All Tasks
To view all tasks, use the following command:

sh

Copy
cargo run list
Remove a Task
To remove a task, use the following command:

sh

Copy
cargo run remove <task_id>
Replace <task_id> with the index of the task you wish to remove.

Project Structure
src/main.rs: Entry point of the application.

src/todo.rs: Module containing the core functionalities of the todo app.

Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. We appreciate your help!

License
This project is licensed under the MIT License. See the LICENSE file for more details.
