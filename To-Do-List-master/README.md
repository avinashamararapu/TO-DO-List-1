



## Synopsis

Just a basic todo app that I wrote using vanilla **JavaScript** so there's not much to it.

## Code Example

```
var taskCompleted = function() {               // Mark a task as complete
  var listItem = this.parentNode;              // We assign it for readability
  completedTasksHolder.appendChild(listItem);  // Append the task list item to the #completed-tasks
  bindTaskEvents(listItem, taskIncomplete);    // We bind it to the opposite holder
};





