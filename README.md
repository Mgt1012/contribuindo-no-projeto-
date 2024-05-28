# contribuindo-no-projeto-
# todo.py
tasks = []

def add_task(task):
    tasks.append(task)
    print(f'Task "{task}" added.')

def show_tasks():
    print("Tasks:")
    for task in tasks:
        print(f"- {task}")

if __name__ == "__main__":
    while True:
        action = input("Type 'add' to add a task or 'show' to see all tasks: ")
        if action == "add":
            task = input("Enter a task: ")
            add_task(task)
        elif action == "show":
            show_tasks()
        else:
            print("Invalid action.")

git add todo.py
git commit -m "Initial commit: add todo.py"]


git push origin main
