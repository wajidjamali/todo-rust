# 📝 todo-rust

A **blazingly fast** and easy-to-use **command-line todo app** written in Rust.  
Manage your daily tasks right from your terminal, no GUI, just power.

---

## 📦 Features

- ✅ Add one or more tasks at once
- 📋 List all, done, or pending tasks
- ✏️ Mark tasks as done or undone
- ❌ Remove specific tasks or clear them all
- 🔃 Sort tasks by status or order

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/wajidjamali/todo-rust.git
cd todo-rust
```

## Installation

To install this program, you'll need Rust installed on your system.
Once Rust is installed, you can build the program using Cargo:

```bash
cargo build --release
```

After successful compilation, you can copy the executable to a directory in your PATH, for example:

```bash
cp target/release/todo-rust /usr/local/bin/todo
```
## 2. Build the App

```cargo build --release
The compiled binary will be located at:
./target/release/todo-rust
```

## Usage

The following commands are available:

- `list` or `list-all`: Lists all the tasks.
- `list-done`: Lists only the completed tasks.
- `list-undone`: Lists only the tasks that are not completed.
- `add <task>`: Adds a new task.
- `rm <task_index>`: Removes the task at the specified index.
- `rm-all`: Removes all tasks.
- `done <task_index>`: Marks the task at the specified index as done.
- `undone <task_index>`: Marks the task at the specified index as undone.
- `sort` or `sort-asc`: Sorts the tasks in ascending order.
- `sort-dsc`: Sorts the tasks in descending order.
- `sort-done` or `sort-done-asc`: Sorts the completed tasks in ascending order.
- `sort-done-dsc`: Sorts the completed tasks in descending order.
- `sort-undone` or `sort-undone-asc`: Sorts the tasks that are not completed in ascending order.
- `sort-undone-dsc`: Sorts the tasks that are not completed in descending order.

# 📄 License
See the LICENSE file for license rights and limitations.

# 🧑‍💻 Author
Made with ❤️ by Abdul Wajid
