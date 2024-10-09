todo_list = []
def add_task(task):
    todo_list.append(task)
    print(f'Task "{task}" added to the list.')
def show_tasks():
    if todo_list:
        print("Here are your tasks:")
        for i, task in enumerate(todo_list, 1):
            print(f"{i}. {task}")
    else:
        print("Your task list is empty.")
# Add tasks to the list
add_task("Buy groceries")
add_task("Finish homework")
add_task("Call a friend")

# Show all tasks in the list
show_tasks()
