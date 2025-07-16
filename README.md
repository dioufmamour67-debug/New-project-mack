function addTask() {
  const input = document.getElementById("taskInput");
  const task = input.value.trim();

  if (task !== "") {
    const taskList = document.getElementById("taskList");
    const li = document.createElement("li");
    li.textContent = task;
    taskList.appendChild(li);
    input.value = "";
  }
}
# New-project-mack
Moderne sociaux 
![ballon-dor](https://github.com/user-attachments/assets/935330a2-56f6-496b-9918-7bd1cc7874a3)
