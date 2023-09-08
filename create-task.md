# Create Task

## Usage

- Create an action file in your repository, you can use [example.yml](./example.yml) as a template.
- Set the following;
  - title: the title of the task, this is required
  - description: the description for the task, can be empty
  - labels: a list of labels to add to the task, can be empty
  - priority: the priority of the task, required, can be 1, 2, 3 or 4 but is reversed in Todoist so enter 4 gets a priority of 1 (weird eh!?)
  - due_string: the due date for the task in todoist speak (i.e. today, next week etc), can be empty
  - project_id: the numeric id of the project you want to assign the task to, required

## Notes

- The token is acquired from your repository secrets, this is passed to the action but not printed in the logs.
