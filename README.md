# todo

1) Introduction

This script is a simple command-line todo list manager. it include methods that enable it to create tasks, update and delete them from the list as well as listing the tasks. We differentiate the task according to its ID number, title, description, place, date and time, and other indicators that show whether or not it has been completed.


2) Data Storage

Tasks are saved in a file that is called tasks and is structured as a plain text file. txt. A description of each elaboration is contained in one line with fields separated by the | symbol. The fields are as follows:The fields are as follows:

- ID
- Title
- Description
- Location
- - Time and date of the due:

- Completion Status

3) Code Organization

:The script is organized into functions, each responsible for a specific operation:

- ld_tsk: It loads tasks from the file…
- sv_tsk: Persists all the tasks to the specified file.
- gen_id: It makes identification of new tasks created to be unique.
- crt_tsk: Asks the user about the task details and then adds it into the system as a new task.
- upd_tsk: This command makes the user to edit a task out of the list that is currently in use.
- del_tsk: Removes a task from the list by using the Task-ID as parameter.
- shw_tsk: PIN: Shows the specific task accomplished by an ID.
- lst_tsks: See the difference between a comprehensive list of activities as well as the completed and uncompleted activities of a specific day.
- srch_tsk: A keyword search for a given title involves searching the database for tasks that have a similar title as the indicated task.

3)runing this program

chmod +x todo. sh
