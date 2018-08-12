## Submission Details
#### by Ambar Prajapati

### Assessment 1:		
> **Completed**: Technical and functional requirements as specified.
#### Functional Requirements:
* **Done**: A user must be able to create a task.
	* **Done**: A user must not be able to create a task with no title.
* **Done**: A user must be able to delete a task.
* **Done**: A user must be able to complete a task.
	* **Done**: A user must be able to see a visual representation of a completed task.
	* **Done**: The complete button should be disabled if the task is completed.
* **Done**: A user must be able to see a list of all their tasks.
* **Done**: The add-task input field must clear after adding a task.
* **Done**: After adding a new task, the task must be added to the list of visible tasks.

#### Technical Requirements :
* **Done**: Create a react app from scratch using create-react-app.
* **Done**: Use Components.
* **Done**: Use State.
* **Done**: Use Props.
* **Done**: Use Map.
* **Done**: Use Classes
* **Done**: Use In-line styles
* **Done**: Use Conditional Classes (css)

<img src="https://github.com/ambarprajapati/submission/blob/master/image1.jpg" />

### Assessment 2:		
> **Completed**: Technical and functional requirements as specified using redux.
* **Done**: Keep track of tasks using redux.
* **Done**: Create, Complete, and Delete tasks using action creators with redux.

<img src="https://github.com/ambarprajapati/submission/blob/master/image2.jpg" />


### Assessment 3:
### Functionality

* A user should be able to click on a task to be taken to a detailed view of that task:
  * A user should be able to modify the title of a task.
  * A user should be able to add/modify the description of a task.
  * A user should be able to save changes to a title/description:
    * This should navigate the user to the main list of tasks after saving changes.
  * A user should be able to cancel text changes:
    * This should set the input fields' values back to their original value.
  * A user should be able to delete a task:
    * This should navigate the user back to the main list of tasks after deleting a task.
  * A user should be able to complete a task:
    * This should navigate a user back to the main list of tasks after completeing a task.
* A user should be able to click on a link to be taken back to the main list of tasks from the detailed view.


> **Completed**:
* **Done**: Use Material-UI (current version) for user interface components.
* **Done**: Use API to manage tasks. <br>Note : The API code to create, fetch, update, complete, and delete tasks uses `redux`,  `superagent` and `thunk`. 
> **To-do/Pending**:		
<br>1. Implement detailed view of a task as per specified functionality. Use `react-router-dom`:
<br>2. Replace  `thunk`, `superagent` with `redux-saga`, `isomorphic-fetch` 

<img src="https://github.com/ambarprajapati/submission/blob/master/image3.jpg" />
