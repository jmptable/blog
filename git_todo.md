---
desc: git-based system for todo files
wip: true
---
The stuff I like from Workflowy, but under my control.

* removing a task:
	git rm _task_
	git commit -m "finished task _task_."
* adding a task:
	cat _whatever data_ > _task_
	git add _task_
	git commit -m "new task _task_."
